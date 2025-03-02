**Steps to Run the Project:**

1) Install Microsoft Visual C++ Redistributable for VS
2) Install NVIDIA GPU driver
3) Install Anaconda, Open Anaconda Prompt 
4) conda create -n tensorflow_env python==3.10
5) conda activate tensorflow_env
6) conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0
7) pip install --upgrade pip
8) pip install "tensorflow<2.11"
9) clone the repo, keep Music_Genre_Classification as the only folder and the root folder, delete all the remaining folders and open our Music_Genre_Classification in VS Code
10) Install python extension
11) Open Train_Music_Genre_Classifier.ipynb
12) Select Kernel -> Python Environments -> tensorflow_env
13) Copy the path of Music_Genre_Classification and paste it in Anaconda after "cd". make sure you are in tensorflow_env
14) In Anaconda run following command:
pip install -r requirement.txt
15) Copy genres_original folder from dataset into the project, Copy Test_Music folder and Trained_model.h5 from the drive into the project.
16) In Train_Music_Genre.ipynb file, in 2nd code snippet, replace "Trained_model.keras" by "Trained_model.h5"
Do the same in Music_Genre_App.py line 12
17) Delete the file "genres_original / jazz / jazz.00054.wav"
18) Run the Project
