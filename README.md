
<img width="100" src="https://user-images.githubusercontent.com/62889318/183091713-7c2f9f75-1d98-48b1-b5e0-a4fdbc771f08.png">

# SMS-Spam-API
## Steps to Access
To access our application you can either download the [android application]().

- [Backend API Postman Documentation](https://documenter.getpostman.com/view/18833270/UVeAtoRi)
- [Android App](https://github.com/harshjadon9/XSpam-Frontend/blob/main/android/app/release/XSpam.apk)
- [Google Slides Presentation](https://docs.google.com/presentation/d/1VxxluxgWW_ybU4xPmC5XAu8mPKcrk6lv/edit#slide=id.g83372e3e9c_0_0)
- [Video Demonstration](https://drive.google.com/file/d/1FPoRCECrZcSqU0Shb-bBs8sFwb-31hp5/view?usp=sharing)

## Motivation 
Confidence in an online world
Our lives have been subjected to digital attacks more than ever before.

In recent times, during the lockdown period, a lot of citizens were victims of an SMS scam. 
The victim receives an SMS as below:

> "Dear customer, your xxx bank account will be suspended! Please Re KYC Verification Update click here link http://446bdf227fc4.ngrok.io/xxxbank".

Once a victim clicks on the link and logs in to the phishing website using internet banking credentials, the attacker generates OTP for 2FA or two factor authentication which is delivered to the victim's phone number. The victim then enters this OTP in the phishing site, which the attacker captures and Finally, the attacker gains access to the victim's account using the OTP and performs fraudulent transactions.

Use your creativity to design and develop a mobile app which can automatically scan through SMS texts and detect possible fraud and phishing attacks and suggest the user not to click on such a link. Additionally, the app can have a "Report This" option which submits the incident to Cyber Security Department (CERT-In) for further investigation. How will you detect false positives in reporting such incidents?

## ❓ Problem Statement
To design and develop a mobile app that can automatically scan through SMS texts to detect possible fraud and phishing attacks and suggest the user not to click on such a link.

## 👌 What it does/ Features:
- Spam and Malicious SMS Detection using BiLSTM Deep Learning Model with 98% Efficiency
- "Report This" option which submits the incident to Cyber Security Department (CERT-In) for further investigation
- User can see the SIM on which the spam message is coming
- Easy to understand Minimilastic and Interactive UI/UX Design 

## Proposed Approach:
<img src="./mockups/hackathon.png" >


## Mockups
<table>
    <tr>
        <td><img width="100%" alt="image" src="https://user-images.githubusercontent.com/62889318/183091009-bf0891f8-9233-4dac-9657-01a76708659a.png"></td>
        <td><img width="100%" alt="image" src="https://user-images.githubusercontent.com/62889318/183091040-4eb5334d-bf89-4afa-ba6e-4d97220f94ff.png"></td>
        <td><img width="100%" alt="image" src="https://user-images.githubusercontent.com/62889318/183091071-fef3ce5c-712f-4127-aefa-74d568b2da4d.png"></td>
    </tr>
    <tr>
        <td><img src="./mockups/4.jpg"></td>
        <td><img src="./mockups/5.jpg"></td>
        <td><img src="./mockups/6.jpg"></td>
    </tr>
</table>

## Tech Stack
React Native, Python, Flask, Tensorflow, Heroku, Git, Numpy, Pandas, Scikit, Matplotlib
Technologies : Deep Learning, Bi-LSTM


## Steps to run locally
Clone the repo in your local machine and setup python and flutter environment. Create .env file similar to .env.sample file with all the required fields.

### Mobile Application
1. Go into `app/` directory by doing `cd app` in terminal.
2. Configure firebase for android by folllowing the [doumentation](https://firebase.flutter.dev/docs/installation/android/).
3. Write `flutter run` in the terminal to start the application.

### Flask Server
1. Install all the required packages in python virtual enviroment `pip install -r requirements.txt`
2. Run `python app.py` in the root directory of the project.

## Contributors
- [Harsh Jadon](https://github.com/harshjadon9)
- [Karnik Kanojia](https://github.com/karnikkanojia)
- [Eshaan Agarwal](https://github.com/eshaanagarwal)
