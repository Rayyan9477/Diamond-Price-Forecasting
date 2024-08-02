# Diamond Price Forecasting: Data Science and Machine Learning Approach

- [LinkedIn](https://www.linkedin.com/in/rayyan-ahmed9477/)
  

## About The Project

The Diamond Price Prediction project is an end-to-end data science initiative focused on forecasting diamond prices using advanced machine learning techniques. By conducting extensive exploratory data analysis (EDA), this project aims to uncover the key factors that influence diamond pricing. Leveraging data analytics, it provides accurate and valuable price predictions, offering critical insights to both buyers and sellers in the diamond market. Through the integration of machine learning models, this project enhances decision-making processes, ensuring informed transactions in the highly valuable diamond industry.

## About the Data

The dataset The goal is to predict the price of a given diamond (Regression Analysis).

There are 10 independent variables (including id):

 - id: the unique identifier of each diamond
 - carat: Carat (ct.) refers to the unique unit of weight measurement used exclusively to weigh gemstones and diamonds.
 - cut: Quality of Diamond Cut
 - color: Color of Diamond
 - clarity: Diamond clarity is a measure of the purity and rarity of the stone, graded by the visibility of these characteristics under 10-power magnification.
 - depth: The depth of the diamond is its height (in millimetres) measured from the culet (bottom tip) to the table (flat, top surface)
 - table: A diamond's table is the facet which can be seen when the stone is viewed face up.
 - x : Diamond X dimension
 - y: Diamond Y dimension
 - z: Diamond Z dimension

### Target variable: 
- price: Price of the given Diamond.
  

Dataset Source Link : ```https://www.kaggle.com/competitions/playground-series-s3e8/data?select=train.csv```

## Built With

 - Pandas
 - Numpy
 - Scikit-learn
 - Flask
 - DVC
 - MLFlow
 - Seaborn
 - Matplotlib


## Installation Steps

### Option 1: Installation from GitHub

Follow these steps to install and set up the project directly from the GitHub repository:

1. **Clone the Project or Download the Code**
   - From Github download the code or clone repo 
 

2. **Create a Virtual Environment** (Optional but recommended)
   - It's a good practice to create a virtual environment to manage project dependencies. Run the following command:
     ```
     conda create -p <Environment_Name> python==<python version> -y
     ```

3. **Activate the Virtual Environment** (Optional)
   - Activate the virtual environment based on your operating system:
       ```
       conda activate <Environment_Name>/
       ```

4. **Install Dependencies**
   - Navigate to the project directory:
     ```
     cd [project_directory]
     ```
   - Run the following command to install project dependencies:
     ```
     pip install -r requirements.txt
     ```

5. **Run the Project**
   - Start the project by running the appropriate command.
     ```
     python app.py
     ```

6. **Access the Project**
   - Open a web browser or the appropriate client to access the project.
   - http://localhost:8080
  
![Home](static\Home.png)

![Output](static\Output.png)
<br><br>

##  Usage and Configuration

This project requires Amazon Web Services Access Key ID and Secret Access Key for interacting with AWS services. Follow these steps to configure your project to use AWS keys:

1. **Obtain Your AWS Access Key ID and Secret Access Key**:
   - Log in to the AWS Management Console.
   - Open the IAM (Identity and Access Management) dashboard.
   - Create a new IAM user or use an existing one.
   - Attach the necessary policies to the user.
   - Generate an access key for the user. Save these keys securely.

2. **Configuration**:
   - Store your AWS Access Key ID and Secret Access Key securely. Do not hardcode them directly in your code or expose them in public repositories. Instead, use environment variables or a configuration file to manage them securely.


## Contact

Rayyan Ahmed - [rayyanahmed265@yahoo.com](rayyanahmed265@yahoo.com)

