================= Performance evaluation of Terapixel rendering in Cloud (Super)computing =================

========= Description =========
This project is about the EDA process of the image rendering on to the cloud.
The code used to perform the analysis is Python Programming Language


========= Files in Main Project =========
1. Code - TeraPixel Original .ipynb     --> The code with some explanation in the form of .ipynb to run it later.
2. Report - Report.pdf--> The Details report of the Analysis
3. Structured Abstract_Key Images - Structured Abstract --> The Structured Abstract with the Key images which give an outline to the main report.

========= Running the Code =========
1. Download the three .csv files (raw data) using the below given sharepoint link. A proper Newcastle University account is required.
https://newcastle-my.sharepoint.com/personal/nmf47_newcastle_ac_uk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fnmf47%5Fnewcastle%5Fac%5Fuk%2FDocuments%2FTeraScope&ga=1

2. Move the downloaded .csv files into a particular folder and copy the location of the respective files.

3. Open the "Code - TeraPixel Original .ipynb" file in Python Notebook and give the location of the .csv datasets in the python code cell 2. 
   The code looks like below.
   Edit the location between the double quotes ("").

  application_file = pd.read_csv("application-checkpoints.csv")
  gpu_file = pd.read_csv("gpu.csv")
  task_xy = pd.read_csv("task-x-y.csv")

4. In the Python Notebook options bar select "Cell" and choose "Run All".

5. Now all the code cells will give appropriate outputs.




