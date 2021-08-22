
# Heart Failure Detection

Machine learning applied to medical records, in particular, can be an effective tool both to predict the survival of each patient having heart failure symptoms, and to detect the most important clinical features (or risk factors) that may lead to heart failure.

## Requirements
1. Python 3.5+
2. Jupyter Notebook
3. Visual Studio Code
5. Knowledge on Heroku for deployment purpouse 


## Steps from starting till deployment

1. Clone the repository to your local system, copy the link of this repository and type in the command

```bash
  git clone <repository_link>
```
to install the required tools for this project enter the command
```bash
  pip install -r requirements.txt
```
2. For information about the code and steps followed feel free to open the `HeartFailureDetection.ipynb` file in your Jupyter Notebook. I have used different algorithms and used the model with highest accuracy.

3. Saving the model, joblib library is used for saving the model

```bash
  import joblib
  filename = 'heart_failure_detect_model.pkl'
  joblib.dump(rf, filename)
```
4. After saving the model we need to load the file for the prediction pupouses, for that we have used Visual Studio Code IDE

5. Once opened you can add the folder in the Visual Studio Code, feel free to open the code and try to understand it and in the terminal go to inside the folder and enter the command 

```bash
  python heart.py
```
6. Viewing the app
click the link that is generated in your terminal 
(or)
Enter the following link in the browser

```bash
  http://127.0.0.1:5000
```
7. Deployment in heroku:-
Go to this link `https://id.heroku.com/login` and create an account with the same github account name

8. Select Create an app and type the name of the app and select United States and click create app
9. Select the `Deploy` tab and in the 2nd section click GitHub and in the search bar enter the name of the repository `HeartFailureDetection` and click on connect 
10. Scroll down to the bottom in the Manul Deploy section click `Deploy Branch` and wait till the process gets completed, finally after everything gets done you can see the `view` button click on that to navigate to the app
 
  
## Screenshots

![App Screenshot](file:///C:/Users/chand/OneDrive/Pictures/Screenshots/Screenshot%20(5).png)

![App Screenshot](file:///C:/Users/chand/OneDrive/Pictures/Screenshots/Screenshot%20(7)_LI.jpg)

![App Screenshot](file:///C:/Users/chand/OneDrive/Pictures/Screenshots/Screenshot%20(8)_LI.jpg)

  
  