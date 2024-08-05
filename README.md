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
