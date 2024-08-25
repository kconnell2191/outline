# outline
Mobile App Development 
Project Outline for Quick-Use Hydraulics Calculator for Firefighters
1. Project Description
Project Name: FirePumpCalc

Description:
FirePumpCalc will be a mobile application designed to assist firefighters in conducting efficient and accurate pumping operations during emergencies. It provides quick and reliable calculations for various hydraulic operations, ensuring optimal performance of firefighting equipment.

2. Problem Addressing
Problem Statement:
Firefighters often face challenges in performing precise hydraulic calculations under pressure, which can lead to inefficiencies or errors during pumping operations. FirePumpCalc aims to solve this issue by providing an easy-to-use tool that delivers accurate hydraulic calculations quickly, enhancing the effectiveness and safety of firefighting efforts.

3. Platform
Platform:
The app will be developed for both Android using Flutter. This ensures that the app reaches a wide audience and provides a consistent user experience across different devices.

4. Front/Back End Support
Front-End:

Framework: Flutter
Languages: Dart
UI Components: Custom components, Material Design widgets
Back-End:

Server: Firebase
Database: Firestore
APIs: RESTful APIs for communication between front-end and back-end
Hosting: Firebase Hosting
5. Functionality
Core Features:

User Authentication: Sign-up, login, password recovery
Hydraulic Calculations:
Pressure loss calculations
Flow rate calculations
Pump discharge pressure calculations
Nozzle pressure calculations
Saved Calculations: Ability to save and retrieve past calculations for reference
Settings: User settings and preferences
Notifications: Push notifications for app updates and critical information
Additional Features:

Tutorials: In-app guides and tutorials for new users
Offline Mode: Allowing the app to function without an internet connection
Analytics: Integration with analytics tools to track user behavior
6. Design (Wireframes)
Wireframes:

Home Screen: Quick access to main calculation tools
Login Screen: Simple layout for user authentication
Calculation Screen: Input fields for hydraulic parameters and real-time result display
History Screen: List of saved calculations with options to view or delete
Settings Screen: Options to customize user preferences

Inputing formulas for pump operations according to standard Hydraulic Pump Operation for Firefighter standards and using department
specific SOPs to tailor it to local protocol. 
  PDP = FL + NP + APP +/- EL
    Where FL = Friction Loss
          NP = Nozzle Pressure
          APP = Appliance
          EL = ELevation
      FL = C x (Q^2) x L
        C = Coefficient which is based on the diameter of hose being utilized. 
            Coefficents are as follows
              1 3/4 = 15.5
                  2 = 8
                2.5 = 2
                  3 = 0.8
                  4 = 0.2
                  5 = 0.08
        Q = Gallons per Minute divided by 100 for example 400GPM would be 4
        L = Length of hose divided by 100 

  If given the scenario with a smooth bore, the GPM will be calculated as follows
      GPM = 29.7 x d^2 x square root of NP
        Where 29.7 is a constant, d = the diamter of the discharge, and NP is the nozzle pressure. 

Formal Outline:

1.	Project Outline:

The hydraulics calculator app is designed specifically for firefighters conducting pumping operations. Its purpose is to simplify and speed up hydraulic calculations needed for efficient fire suppression. The app enables users to input relevant variables, such as hose length, pressure, and nozzle type, and automatically computes accurate hydraulic results. The target audience includes firefighters, fire engineers, and other emergency personnel requiring real-time hydraulic calculations during critical operations.

2.	Problem Addressing:

Firefighters often face high-pressure situations where accurate hydraulic calculations are essential to ensure adequate water flow during firefighting operations. Manually performing these calculations can be time-consuming and prone to error, especially under stress. The app addresses this problem by providing a reliable and efficient tool for performing hydraulic calculations instantly, ensuring the right water pressure and flow rate for effective firefighting, ultimately helping save lives and property.

3.	Platform:

The hydraulics calculator app will run on the Android platform. This platform was chosen due to its widespread use, versatility, and compatibility with various devices that firefighters and emergency personnel may use. Android offers strong support for mobile applications, providing the necessary tools and frameworks for building a robust, user-friendly app that can operate efficiently in both offline and online environments. This ensures the app can be deployed and used effectively in real-time emergency scenarios.

4.	Front/Back End Support:

•	Front-End Technologies: The app's user interface will be developed using Java and XML. Java will handle the logic and interactions, while XML will define the layout, ensuring a smooth and intuitive user experience for firefighters using the app during operations.

•	Back-End Technologies: The back end will use SQLite to store and manage data locally on the device. This ensures that hydraulic calculation records, settings, and other relevant data are accessible even without internet connectivity, which is crucial during emergency situations.

5.	Functionality:
The hydraulics calculator app includes several key features:
•	Input Fields for Hydraulic Parameters: Users can input critical parameters such as hose length, nozzle pressure, water flow rate, and friction loss.

•	Real-Time Calculations: The app instantly performs accurate hydraulic calculations based on the entered parameters, providing firefighters with essential data for their operations.

•	Data Storage: The app stores previous calculations and settings locally using SQLite, allowing users to retrieve past data for future reference, even when offline.

6.	Design (Wireframes):
The wireframes for the hydraulics calculator app outline a user-friendly interface tailored for quick input and access during emergency situations:
•	Home Screen: Features options to input hydraulic parameters (hose length, pressure, flow rate) with large, easy-to-access buttons for rapid use in the field.

•	Calculation Screen: Displays real-time results, including pressure and flow data, with clear visuals and color coding.

•	Data Storage/History Screen: Allows users to view past calculations and access stored data for reference during operations.
The design focuses on simplicity, speed, and ease of use under pressure.
