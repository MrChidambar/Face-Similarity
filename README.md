Project Name: Which Bollywood Celebrity You Look Like
A deep learning-based Streamlit web app that can tell which Bollywood celebrity your face resembles.

Face recognition involves identifying and verifying people in a photograph by their face. It is a task easily performed by humans, even under varying light conditions and when faces are altered by age or obscured by accessories and facial hair. Nevertheless, it has remained a challenging computer vision problem for decades until recently.

Deep learning methods can leverage very large datasets of faces to learn rich and compact representations, allowing modern models to perform as well as, and later outperform, the face recognition capabilities of humans.

In this project, you will explore the problem of face recognition and how deep learning methods can achieve superhuman performance in identifying similar faces.


This project identifies similar faces by checking various aspects in pictures, including face shape, nose, eyes and mouth; face position in the picture; skin color (including lighting); color and hair; and cosine similarity.

Dataset Used: Kaggle Dataset

Some Real-Time Demos:
Web app look

Workflow

Let's check some images:

Workflow

Workflow

This project performs well, as shown by the results. 😀

The fun part is I look like Riteish Deshmukh! 😄😁

Steps to Run This Project:
You can also use other images instead of Bollywood celebrities.

STEP 01: Clone the repository:

bash
git clone https://github.com/entbappy/Which-Bollywood-Celebrity-You-look-like.git
STEP 02: Create an environment:

bash
conda create -n celebrity python=3.7 -y
STEP 03: Install the requirements:

bash
pip install -r requirements.txt
STEP 04: Download the data from the link and keep it in your project directory. Ensure all the folders for actresses are within a single folder called data.

STEP 05: Execute this command one time if you are not changing the data:

bash
python run.py
STEP 06: To start the web app, run the following command:

bash
streamlit run app.py
Yes! Now you can start predicting. 🙂
