# GitHub Kaggle Project

### **👥 Team Members**

| Name | GitHub Handle | Contribution |
| - | - | - |
| Annabelle Ni | @acni100 | Model Development, Evaluation, and Performance Tuning |
| Belle Lopez | @Belleairr | 
| Henry Avila | @HenryA01 | Attempted image augmentation with the dataset |
| Liam Bagabag | @lbzfran | Tested Pre-trained models, Model Training |
| Rebecca Su | @rebecca-123 | Model Development/Fine-Tuning and Model Evaluation |
| Sonya Kim | @sonyakim-dev | 

---

## **🎯 Project Highlights**

**Example:**

* Built a Convolutional Neural Network using Tensorflow Keras to solve Equitable AI for Dermatology.
* Achieved an F1 score of \[final score\] and a ranking of \[insert ranking out of participating teams\] on the final Kaggle Leaderboard.
* Used Pandas and Matplotlib to interpret model decisions
* Implemented Keras’ Image Transformer and Early Stopping to optimize results within compute constraints

🔗 [Equitable AI for Dermatology | Kaggle Competition Page](https://www.kaggle.com/competitions/bttai-ajl-2025/overview)
🔗 [WiDS Datathon 2025 | Kaggle Competition Page](https://www.kaggle.com/competitions/widsdatathon2025/overview)

---

## **👩🏽‍💻 Setup & Execution**

**Provide step-by-step instructions so someone else can run your code and reproduce your results. Depending on your setup, include:**

To setup our notebook environment:

```sh
git clone https://github.com/lbzfran/UCLA_AJL_Team-3
cd ./UCLA_AJL_Team-3

# windows
py -m venv .venv 

# linux
python -m venv .venv

pip install -r ./requirements.txt

# windows
 .venv/Scripts/activate.ps1

# linux
source .venv/bin/activate

jupyter notebook
```

---

## **🏗️ Project Overview**

Often, dermatology AI tools underperform for people with darker skin tones due
to a lack of diverse training data, leading to diagnostic errors, delayed treatments,
and health disparities for underserved communities.
Our project is among many for the competition seeking to combat that, and garner
a more diverse and open aid to the community.

---

## **🧠 Model Development**

Models Used:
* CNN with simple architecture (>10 layers)
* CNN with transfer learning (InceptionV3, MobileNet)

Hyperparameter tuning strategies:
* Early Stopping
* Reducing Learning Rate

Training Setup:
* 80/20 Train/Test Split
* Rescaling Image
* Image Transformation (rotation, shifting, brightness, etc.)
* F1 Score

---

## **📈 Results & Key Findings**

- Accuracy: ~30%
- F1 Score: >0.2

---

## **🖼️ Impact Narrative**

**Answer the relevant questions below based on your competition:**

**AJL challenge:**

As Dr. Randi mentioned in her challenge overview, “Through poetry, art, and storytelling, you can reach others who might not know enough to understand what’s happening with the machine learning model or data visualizations, but might still be heavily impacted by this kind of work.”
As you answer the questions below, consider using not only text, but also illustrations, annotated visualizations, poetry, or other creative techniques to make your work accessible to a wider audience.
Check out [this guide](https://drive.google.com/file/d/1kYKaVNR\_l7Abx2kebs3AdDi6TlPviC3q/view) from the Algorithmic Justice League for inspiration!

1. What steps did you take to address [model fairness](https://haas.berkeley.edu/wp-content/uploads/What-is-fairness_-EGAL2.pdf)? (e.g., leveraging data augmentation techniques to account for training dataset imbalances; using a validation set to assess model performance across different skin tones)
Part of the work was done already for us by Kaggle, but we had to ensure the dataset
we're working with in the first place is representative of all possible groups
of people. To complement this however, we transform the oncoming images,
increasing the possible ranges of colors by some margin in order to generate
better and unbiased results.

3. What broader impact could your work have?
In a broader scale, our work could definitely have an impact with how decisions are made
in health care, allowing for more accurate and non-biased decision making to occur.

---

## **🚀 Next Steps & Future Improvements**

* What are some of the limitations of your model?
Our model's biggest weakness is its inaccuracy: Unfortunately, we were
unable to come up with a model that is at least able to achieve >50% accuracy,
as was our intention coming into the project.
* What would you do differently with more time/resources?
We focused a lot of our attention on the model, but I feel like for this project,
it was definitely more important to process the data appropriately.
* What additional datasets or techniques would you explore?
In the future, it might help to commit more time to processing the data, and
constructing a simpler model as opposed to dedicating our manpower on pre-trained
models whose training took up a lot of time overall.

---

