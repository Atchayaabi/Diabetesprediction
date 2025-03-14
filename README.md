<div align='center'>
  

  <h1>Diabetes Prediction Streamlit App</h1>

  <p>
The Diabetes Prediction App is a tool that predicts the probability of a patient having diabetes based on diagnostic measurements. This tool is intended for females above the age of 21 years, of Pima Indian heritage, and uses a dataset from the National Institute of Diabetes and Digestive and Kidney Diseases.
  </p>
  

<!-- Badges -->


<a href="https://priyanshu88-diabestes-prediction-streamlit-app-main-5komds.streamlit.app/" target="_blank">![](https://img.shields.io/website-up-down-green-red/http/monip.org.svg)</a>
![](https://img.shields.io/badge/Maintained-Yes-indigo)
![](https://img.shields.io/github/forks/Priyanshu88/Diabetes-Prediction-Streamlit-App.svg)
![](https://img.shields.io/github/stars/Priyanshu88/Diabetes-Prediction-Streamlit-App.svg)
![](https://img.shields.io/github/issues/Priyanshu88/Diabetes-Prediction-Streamlit-App)
![](https://img.shields.io/github/last-commit/Priyanshu88/Diabetes-Prediction-Streamlit-App)
  
 

</div>

<br />


<!-- Table of Contents -->

## :notebook_with_decorative_cover: Table of Contents

- [Dataset](#signal_strength-dataset)
- [Dependencies](#toolbox-dependecies)
- [Installation](#gear-installation)
- [Usage](#play_or_pause_button-usage)
- [Inputs](#construction-inputs)
- [Outputs](#rocket-outputs)
- [Deployment and Notebook](#triangular_flag_on_post-deployment-and-notebook)
- [License](#balance_scale-license)
- [Contact](#handshake-contact)



## :signal_strength: Dataset

The trained dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective is to predict based on diagnostic measurements whether a patient has diabetes. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage. The dataset can be found on [`Kaggle`](https://www.kaggle.com/datasets/mathchi/diabetes-data-set). It includes following health criteria:

- Pregnancies: Number of times pregnant
- Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- BloodPressure: Diastolic blood pressure (mm Hg)
- SkinThickness: Triceps skin fold thickness (mm)
- Insulin: 2-Hour serum insulin (mu U/ml)
- BMI: Body mass index (weight in kg/(height in m)^2)
- DiabetesPedigreeFunction: Diabetes pedigree function
- Age: Age (years)
- Outcome: Class variable (0 or 1)

### Details
- Number of Instances: 768
- Number of Attributes: 8 plus class
- Missing Attribute Values: Yes
- Class Distribution: (class value 1 is interpreted as "tested positive for diabetes")



## :toolbox: Dependecies

`streamlit==0.88.0`

`pandas==1.3.3`

`numpy==1.21.2`

`matplotlib==3.4.3`

`plotly==5.3.1`

`seaborn==0.11.2`

`scikit-learn==0.24.2`

`joblib==1.1.0`

`scipy==1.7.3`

`torch==1.9.1`

`torchvision==0.10.1`


## :gear: Installation

Clone the repository and install the required dependencies using the following commands:

```bash
git clone https://github.com/Priyanshu88/Diabetes-Prediction-Streamlit-App.git
```

```bash
cd Diabetes-Prediction-Streamlit-App
```

```bash
pip install -r requirements.txt
```

```bash
streamlit run app.py
```

## :play_or_pause_button: Usage

1. Open the app in your web browser.
2. Enter the required information in the input fields.
3. Click the 'Predict' button to generate the prediction.



## :construction: Inputs
Click on the link and reboot the tool or run locally and enter your:

* Name: Name of the patient
* Pregnancies: Number of times pregnant
* Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
* Blood Pressure: Diastolic blood pressure (mm Hg)
* Skin Thickness: Triceps skin fold thickness (mm)
* Insulin: 2-Hour serum insulin (mu U/ml)
* BMI: Body mass index (weight in kg/(height in m)^2)
* Diabetes Pedigree Function: Diabetes pedigree function
* Age: Age (years)



## :rocket: Outputs
The app will display one of the following messages:

* "Congratulations! [Name], you are not diabetic."
* "[Name], we are really sorry to say but it seems like you are Diabetic. But don't lose hope, we have suggestions for you." along with a link to the Mayo Clinic's Diabetes Prevention page.




## :triangular_flag_on_post: Deployment and Notebook

This tool has been deployed using [`Streamlit`](https://streamlit.io/). Learn about streamlit deployment [`here`](https://docs.streamlit.io/streamlit-community-cloud/get-started/deploy-an-app). Checkout the notebook repository [`here`](https://github.com/Priyanshu88/Diabestes-Prediction) from where the pickle file has been imployed in the tool.



## :balance_scale: License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Priyanshu88/Diabetes-Prediction-Streamlit-App/blob/main/LICENSE) file for details.



## :handshake: Contact

![](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)

Your Name - [@twitter_handle](https://twitter.com/Priyans75729802?s=09) - 2040020@sliet.ac.in


<hr />
<br />
<div align="center">Don't forget to leave a star ⭐️</div>
