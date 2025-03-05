# A-z Services

## Description  
A-z Services is a mobile application designed to streamline the process of hiring professionals for various home and business services, including plumbing, electrical work, and tutoring. The app provides a user-friendly interface with authentication, real-time service availability, and profile management features.

## Features  
- **User and Admin Account Creation:** Users and service providers can register through OTP verification.  
- **Service Categorization:** Services are organized into categories for easier navigation.  
- **Real-time Availability:** Users can check the live availability of service providers before booking.  
- **Profile Management:** Service providers can update their profiles, including experience, pricing, and availability.  
- **Rating and Reviews:** Users can leave feedback for service providers, enhancing trust and credibility.  

## Installation  
To set up the project on your local system, follow these steps:  

1. **Clone the repository:**  
   Open a terminal and run the following command:  
   ```bash
   git clone https://github.com/Yashwanth127/A-z-Services.git
   ```  
2. **Open the project in Android Studio.**  
3. **Connect Firebase for real-time OTP verification:**  
   - Go to [Firebase Console](https://console.firebase.google.com/).  
   - Create a new Firebase project or use an existing one.  
   - Add your Android app by providing the package name.  
   - Download the `google-services.json` file and place it in the `app/` directory.  
   - Enable **Phone Authentication** in Firebase Authentication settings.  
   - Set up Firebase Realtime Database or Firestore as needed.  

### Firebase Blaze Plan Requirement  
For real-time OTP verification, Firebase requires the **Blaze plan**, which is a pay-as-you-go plan. While Firebase Authentication offers free quota limits, real-time SMS verification involves using third-party services (such as Twilio) that incur costs. By upgrading to the Blaze plan, you can:  
- Remove free-tier limitations on phone authentication.  
- Ensure OTP messages are delivered instantly without delays.  
- Support verification in multiple regions.  

To upgrade, navigate to Firebase Console → Billing → Upgrade to Blaze. Pricing varies based on usage, so it is recommended to monitor usage to avoid unexpected charges.
