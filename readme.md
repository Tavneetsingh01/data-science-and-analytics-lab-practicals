# This Repository contains the lab Programs for On-Going Data Science and Analytics Lab (CSL DC205) Fall 2024
![Python Version](https://img.shields.io/badge/Python-3.10-fdcd3d.svg)
![Conda Version](https://img.shields.io/badge/conda-24.9-43b02a.svg)
## The following are the list of programs with their Jupyter-Notebook and Lecture notes (*Will be updated each week*)

<table style="border-collapse: collapse; width: 100%;">
    <tr>
        <th style="border: 1px solid black; padding: 8px;"><b>Program</b></th>
        <th style="border: 1px solid black; padding: 8px;"><b>Jupyter Notebook</b></th>
        <th style="border: 1px solid black; padding: 8px;"><b>Lecture Notes</b></th>
    </tr>
    <tr>
        <td style="border: 1px solid black; padding: 8px;"><b>Q1. Write a Program to Explore various Data Manipulation Functions provided by Pandas and Visualize the Data Using Seaborn</b></td>
        <td style="border: 1px solid black; padding: 8px;"><a href="pandas_librabry_functions.ipynb">Pandas Library Functions & Visualization Notebook</a></td>
        <td style="border: 1px solid black; padding: 8px;"><i>Currently Under Development</i></td>
    </tr>
    <tr>
        <td style="border: 1px solid black; padding: 8px;"><b>Q2. To predict if a person will purchase a product on a specific combination of Day, Discount and Free delivery using Naïve Bayesian Classifier.</b></td>
        <td style="border: 1px solid black; padding: 8px;"><a href="naive_bayes_classifier.ipynb">Naive Bayes Classifer Notebook</a></td>
        <td style="border: 1px solid black; padding: 8px;"><a href="Lecture%20Notes/Naive_Bayesian_Classifier_Notes.pdf">Naive Bayes Classifier Lecture Notes</a></td>
    </tr>
    <tr>
        <td style="border: 1px solid black; padding: 8px;"><b>Q3. Predict Employee Salary based on Year of Experience using Linear Regression.</b></td>
        <td style="border: 1px solid black; padding: 8px;"><a href="linear_regression.ipynb">Linear Regression Notebook</a></td>
        <td style="border: 1px solid black; padding: 8px;"><i>Currently Under Development</i></td>
    </tr>
     <tr>
        <td style="border: 1px solid black; padding: 8px;"><b>Q4. Predict if a person will buy an SUV based on their Age and Estimated Salary using Logistic Regression.</b></td>
        <td style="border: 1px solid black; padding: 8px;"><a href="Logistic_Regression.ipynb">Logistic Regression Notebook</a></td>
        <td style="border: 1px solid black; padding: 8px;"><i>Currently Under Development</i></td>
    </tr>
    <tr>
        <td style="border: 1px solid black; padding: 8px;"><b>Q5. Does Kyphosis exist after surgery using Decision Tree?</b></td>
        <td style="border: 1px solid black; padding: 8px;"><a href="/decision_tree.ipynb">Decision Tree Notebook</a></td>
        <td style="border: 1px solid black; padding: 8px;"><i>Currently Under Development</i></td>
    </tr>
    <tr>
        <td style="border: 1px solid black; padding: 8px;"><b>Q6. Write a Program to Demonstrate Random Forest Algorithm</b></td>
        <td style="border: 1px solid black; padding: 8px;"><i>This is Maked as your assignment and it will be uploaded before Lab Examination</i></td>
        <td style="border: 1px solid black; padding: 8px;"><i>Currently Under Development</i></td>
    </tr>
    <tr>
        <td style="border: 1px solid black; padding: 8px;"><b>Q7. Predict if a person will buy a SUV based on Age and Estimated Salary using KNN?</b></td>
        <td style="border: 1px solid black; padding: 8px;"><a href="/K_Nearest_Neighbors_Buy_Suv.ipynb">KNN Notebook</a></td>
        <td style="border: 1px solid black; padding: 8px;"><i>Currently Under Development</i></td>
    </tr>
    <tr>
        <td style="border: 1px solid black; padding: 8px;"><b>Q8. Features Extraction from Text using Word Vectorization for Text Semantics?</b></td>
        <td style="border: 1px solid black; padding: 8px;"><a href="/Feature_Extraction_and_Evaluation_Using_SST2.ipynb">1. Feature Extraction and Evalutaion Notebook Using SST2 Dataset</a><hr> 
        <a href="/Feature_Extraction_and_Evaluation_From_Basic_Text_Example.ipynb">2. Feature Extraction and Evalutaion Notebook Using Basic Example</a></td>
        <td style="border: 1px solid black; padding: 8px;"><i>Currently Under Development</i></td>
    </tr>
    <tr>
        <td style="border: 1px solid black; padding: 8px;"><b>Q9. Sentiment Analysis from online news website using simple natural language processing.</b></td>
        <td style="border: 1px solid black; padding: 8px;"><a href="/sentiment_analysis_of_online_news_article.ipynb">Sentiement Analysis Notebook</a></td>
        <td style="border: 1px solid black; padding: 8px;"><i>Currently Under Development</i></td>
    </tr>
    <tr>
        <td style="border: 1px solid black; padding: 8px;"><b>Q10. Use of KmeansClustering algorithm for classifying persons into 3 categories according to their salary.</b></td>
        <td style="border: 1px solid black; padding: 8px;"><a href="#">K-Means Clustering Notebook <i>(Will be Uploaded on Coming Monday)<i></a></td>
        <td style="border: 1px solid black; padding: 8px;"><i>Currently Under Development</i></td>
    </tr>
    <tr>
        <td style="border: 1px solid black; padding: 8px;"><b>Q11. Write a program for demonstrating (Support Vector Machine Classifier) SVM algorithm.</b></td>
        <td style="border: 1px solid black; padding: 8px;"><a href="/SVM_On_Iris_Dataset.ipynb"> SVM Notebook </a></td>
        <td style="border: 1px solid black; padding: 8px;"><i>Currently Under Development</i></td>
    </tr>
</table>

## Environment Setup Guide

This guide provides instructions on how to recreate the development environment for this project using Conda or pip. You can set up the environment using either a YAML file or a requirements text file.

>[!NOTE]
> Here in the lab while coding the notebooks we have used conda as a package manager and miniconda instead of anaconda as distribution because it has less number of pre installed packages and we can install packages as per our requirement. [Miniconda_3 Installation Guide](/Installation_Guides/Summary%20of%20Installation%20and%20Setup%20Steps%20For%20Miniconda3%20(a%20python%20distribution).pdf)

## Table of Contents

- [Using `required-env-packages-list.yml`](#using-required-env-packages-listyml)
- [Using `required-packages-list.txt`](#using-required-packages-listtxt)
- [Using `pip`](#using-pip)

## Using [`required-env-packages-list.yml`](/required-env-packages-list.yml)

To create a Conda environment from a YAML file, follow these steps:

1. **Open your terminal** (Anaconda Prompt or command line).

2. **Navigate to your project directory** where the `required-env-packages-list.yml` file is located:
   ```bash
   cd path/to/your/project  
   ```
3. Create the environment by running the following command:
    ```bash
    conda env create -f required-env-packages-list.yml
    ```
4. Activate the environment with:
    ```bash
    conda activate <environment-name>
    ```
    Replace <environment-name> with the name specified in the YAML file.
## Using [`required-packages-list.txt`](/required-packages-list.txt)
To create a Conda environment from a text file, follow these steps:
1. Open your terminal (Anaconda Prompt or command line).
2. Navigate to your project directory where the [`required-packages-list.txt`](/required-packages-list.txt) file is located:

    ```bash
    cd path/to/your/project
    ```
3. Create a new environment (replace <environment-name> with your desired name):

    ```bash
    conda create --name <environment-name> --file required-packages-list.txt
    ```
4. Activate the environment with:

    ```bash
    conda activate <environment-name>
    ```
## Using pip
If you prefer to use pip to create a virtual environment, follow these steps:
1. Open your terminal.
2. Navigate to your project directory where the [`required-packages-list.txt`](/required-packages-list.txt) file is located:

    ```bash
    cd path/to/your/project
    ```
3. Create a virtual environment (replace <env-name> with your desired name):

    ```bash
    python -m venv <env-name>
    ```
4. Activate the virtual environment:
    1. On Windows:
        - In `PowerShell` :

        ```powershell 
        <env-name>\Scripts\Activate.ps1
        ```
        - In `cmd` :

        ```cmd
        <env-name>\Scripts\activate.bat
        ```
    2. On macOS/Linux:
        ```bash
        source <env-name>/bin/activate
        ```
5. Install the required packages using:
    ```bash
    pip install -r required-packages-list.txt
    ```
>[!NOTE]
> - Ensure you have Conda or Python installed on your system.
> - If you encounter any issues while creating the environment, check that all packages listed in the files are available in your Conda channels or PyPI.
> - It is recommended to regularly update your environment files as you add new packages to ensure reproducibility for other users.
> - By following these instructions, you will be able to set up the development environment required for this project effortlessly. If you have any questions or need further assistance, feel free to open an issue in this repository.

## Contributing
>  :handshake: Feel free to open an issue in this repository if you encounter any issues with any of the notebook code and also if you want to add more programs to the repository then feel free to generate a pull request to this repository. Whole Community will appreciate your feedback and contributions. Thank you 

![jerry and duck handshake](https://tenor.com/en-GB/view/tom-and-jerry-jerry-the-mouse-jerry-shake-hands-handshake-gif-17827738.gif)

## License
This project is licensed under the MIT License. See the [LICENSE](/License) file for details.
   