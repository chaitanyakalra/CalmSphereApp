# A Mental Health Assessment Android Application "_CalmSphere_"

## What does it do?

1) A user not sure of their mental well-being can onboard the application and access various features that will help the user to get better insight of their mental health well being.

2) Chat with our emphatically trained chatbot, the chatbot works as the first point of contact on our application. Upon Chatbot's suggestion or as of the needs of the user, the user can further deep dive into our application.

3) User can book appointments with the therapists on the application, choose between voice-call, video-call, chat or in-person meet with the therapist and pay the fees using all the online payment options on our application.

4) Apart from this, if the user feels that they need a space where they want to  share the problems with the one's who have already gone through or are going through the same problem, they can use our virtual community feature named "Safe Space" on our application.

5) Not everytime a user will login into the application to use the above features, sometimes they just want to read articles related to their problem, listen to some soothing music etc for which our application provides them with the specially curated content for the user. 

## Use-Cases for the Application

### Empathetic Chatbot:


* CalmSphere features an empathetic chatbot designed to be the first point of contact for users.
* The chatbot is trained to engage in empathetic conversations and provide support for three mental health conditions: depression, anxiety, and PTSD.
* It is also equipped to handle situations involving extreme self-harm, offering immediate support and guidance.

### Appointment Booking:


* Based on the chatbot's suggestions or the user's interest, users can book appointments with mental health specialists.
* The selected date, time, user name, and doctor's name are stored in our backend Firebase database, ensuring organized and accessible appointment management.

### Support for Competitive Exam Stress:


* Recognizing the stressful environment of competitive exams like JEE, CAT, etc., CalmSphere aims to provide virtual support to students.
* The app offers resources and support tailored to the unique pressures faced by students in these high-stakes exams.

### Virtual Community "SafeSpace":


* CalmSphere has created a virtual community called "SafeSpace" where users can interact with others who have experienced similar problems or who are currently facing the same challenges.
* This community is proctored by a mental health specialist to ensure a safe and supportive environment.

### Integration with Electronic Health Records (EHRs):


* CalmSphere has the potential to integrate with EHRs, allowing users to securely share their mental health data with healthcare providers.
* This integration would facilitate seamless communication and continuity of care between the platform and traditional healthcare service


## How to use the project (includes the screenshot of the working of the android application)
### Login/Signup and HomePage
![Picture1](https://github.com/ashu1671/CalmshpereApplication/assets/121768454/0185f9e1-12d0-4d01-8e00-254218571650) , ![Picture2](https://github.com/ashu1671/CalmshpereApplication/assets/121768454/c2626142-5d50-496a-bdd1-80d99eddc2ae), ![Picture3](https://github.com/ashu1671/CalmshpereApplication/assets/121768454/73f8a465-2f89-42c7-b92f-44605a2ce589), ![Picture7](https://github.com/ashu1671/CalmshpereApplication/assets/121768454/648242fd-9826-4d69-b62f-ec61ad9a7aa1), ![Picture6](https://github.com/ashu1671/CalmshpereApplication/assets/121768454/95773821-879b-4ab4-af8b-eb8c5d93bc19)

### ChatBot
![Picture8](https://github.com/ashu1671/CalmshpereApplication/assets/121768454/d4f04b80-2b44-4080-92f1-92a56853d586), ![Picture9](https://github.com/ashu1671/CalmshpereApplication/assets/121768454/9e3ff12a-8f31-400c-87b7-d5d91905fae6) , ![Picture10](https://github.com/ashu1671/CalmshpereApplication/assets/121768454/c694bdab-eb8e-4e68-8736-e3fe4226edaf) 

### Booking Appointment
![Picture11](https://github.com/ashu1671/CalmshpereApplication/assets/121768454/87570cfe-d9ca-4dd3-bbe7-2c16415c8f3c), ![Picture12](https://github.com/ashu1671/CalmshpereApplication/assets/121768454/7468dcf0-7fb2-4af2-b20f-a83e88d3f90f), ![Picture13](https://github.com/ashu1671/CalmshpereApplication/assets/121768454/90a7e3d5-7a32-4e3d-9ad5-521cf5542d7c), ![Picture14](https://github.com/ashu1671/CalmshpereApplication/assets/121768454/9d7ccb21-90fd-446c-87d5-1321c7eec3cf), ![Picture15](https://github.com/ashu1671/CalmshpereApplication/assets/121768454/e3797c5f-7594-42a0-a376-d3e35a3c98fc)

### Payement Gateway using Razorpay

![Picture16](https://github.com/ashu1671/CalmshpereApplication/assets/121768454/d32426f8-16fb-4709-84e5-8cc84c4f2989), ![Picture17](https://github.com/ashu1671/CalmshpereApplication/assets/121768454/eed3a9c8-ddad-474c-acaa-13ed6358c9bd), ![Picture18](https://github.com/ashu1671/CalmshpereApplication/assets/121768454/27085ae8-cab4-4fa0-9a6d-2628d32e1338), ![Picture19](https://github.com/ashu1671/CalmshpereApplication/assets/121768454/d53c054e-8046-43b4-83a6-fe98655967c6)

### Virtual Community 

![Picture20](https://github.com/ashu1671/CalmshpereApplication/assets/121768454/293d011b-9696-4bf6-b32b-5d37762e3789), ![Picture21](https://github.com/ashu1671/CalmshpereApplication/assets/121768454/11d41d3d-a67e-4d76-a477-f52249fe7e53), ![Picture22](https://github.com/ashu1671/CalmshpereApplication/assets/121768454/4293c8a4-7a18-4391-bfcc-209475fea53d), ![Picture23](https://github.com/ashu1671/CalmshpereApplication/assets/121768454/cf4cef88-54d1-42a4-985f-9a4d8fbd3adf)



## Dependencies/Libraries

* google-services = { group = "com.google.gms", name = "google-services", version.ref = "googleServices" }
* play-services-auth = { module = "com.google.android.gms:play-services-auth", version.ref = "playServicesAuth" }
* firebase-auth = { group = "com.google.firebase", name = "firebase-auth", version.ref = "firebaseAuth" }
* firebase-firestore = { group = "com.google.firebase", name = "firebase-firestore", version.ref = "firebaseFirestore" }
* import com.google.firebase.firestore.DocumentReference;
* import com.google.firebase.firestore.DocumentSnapshot;
* implementation 'com.razorpay:checkout:1.6.38'
* import com.razorpay.PaymentResultListener 


## Version: CalmSphere 1.0

## Development Environment

This application was developed using Android Studio Iguana | 2023.2.1, a powerful integrated development environment (IDE) tailored for Android development. Android Studio provides a robust set of tools and features that streamline the development process, ensuring a high-quality application.

## Database

The application utilizes Firebase for its backend database. Firebase is a comprehensive app development platform that provides various tools and services to help build, improve, and grow your app. We have implemented the following Firebase services:
* Firebase Authentication: This service provided us secure authentication for users, allowing them to sign in with email and password and Google Sign-in Option. It keeps the user data protected and that, access to the app is restricted to authenticated users only. 
* Firebase Firestore: Firestore is a flexible, scalable database for mobile, web, and server development. We use Firestore to store and sync user data in real-time across all clients. It allows for structured data storage, complex queries, and real-time updates, ensuring that users always have the latest information.



