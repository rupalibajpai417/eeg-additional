# EEG Amplifier Control System
Welcome to the EEG Amplifier Control System project. This Python-based system simulates the control and monitoring of EEG amplifiers used for measuring brain activity. The system allows users to manage multiple EEG amplifiers, configure their settings, and monitor their status.

This project also includes additional features, such as sensor management, saving/loading the state of amplifiers, and error handling.
## Features
1. Add, Remove, and List Amplifiers: Create new amplifiers, remove existing ones, and list all amplifiers currently registered in the system.
2. Adjust Amplifier Settings: Configure settings like sampling rate (256, 512, or 1024 Hz) and gain (1-100).
3. Power Management: Toggle amplifiers on or off to simulate their operational state.
4. Sensor Management: Add or remove sensors to/from amplifiers.
5. Search Functionality: Search for amplifiers by serial number, model, or manufacturer.
6. Update Maintenance Date: Adjust the next maintenance date for amplifiers with validation.
7. Save and Load State: Save the current state of amplifiers to a JSON file and load it at the start of the application.
### Project Structure
1. Amplifier Class: Represents the properties and behavior of an EEG amplifier.
2. Sensor Class: Represents a sensor associated with an EEG amplifier.
3. EEGAmplifierControlSystem Class: Manages the collection of amplifiers and user interactions.
4. Main Function: Contains the user interface for interacting with the system via a menu.
#### Installation
Clone the repository: git clone https://github.com/rupalibajpai417/eeg-additional.git
Navigate to the project directory: cd eeg-additional
Ensure you have Python 3 installed. You can check by running: python --version
##### How to Run
1. Run the program: python main.py
2. A menu will appear, allowing you to interact with the EEG Amplifier Control System. You can add amplifiers, modify their settings, manage sensors, and more. Input your choices based on the menu options.
3. To save the current amplifier state, use the "Save State" option in the menu. To load a previous state, use the "Load State" option.
###### Usage
The main menu offers several options:

1. Add Amplifier: Input amplifier details like serial number, model, manufacturer, sampling rate, gain, etc.
2. Remove Amplifier: Remove an amplifier using its serial number.
3. List Amplifiers: View all currently registered amplifiers.
4. Set Gain/Sampling Rate: Adjust these settings for an amplifier.
5. Toggle Power: Power an amplifier on or off.
6. Search Amplifier: Search by serial number, model, or manufacturer.
7. Add/Remove Sensor: Manage sensors associated with amplifiers.
8. Update Maintenance Date: Adjust the next maintenance date for an amplifier.
9. Save/Load State: Save the amplifier state to a file or load a previously saved state.
####### Error Handling
1. Input validation ensures that settings like gain, sampling rate, and maintenance date are within acceptable ranges.
2. The system also handles invalid inputs gracefully by displaying appropriate error messages.
######## Additional Features
1. Manage sensors for amplifiers.
2. Save and load the state of the system using JSON files.
######### Version Control
This project is managed using Git for version control. You can view the commit history and track changes in the repository.
########## License
This project is open-source and available under the MIT License.
########### Acknowledgement
 Inspired by various open-source projects, including [awesome-readme](https://github.com/matiassingers/awesome-readme), [PurpleBooth](https://github.com/PurpleBooth), [dbader](https://github.com/dbader), [zenorocha](https://github.com/zenorocha), and [fvcproductions](https://github.com/fvcproductions), StackOverflow(https://stackoverflow.com/questions/48077684/accessing-amp-state-json-values), EEG amplifier manual (https://lifelinesneuro.com/wp-content/uploads/2023/01/51262-006-R-40-EEG-Amplifier-User-Manual-Iss1.5.pdf), Features of EEG amplifier (https://www.bitbrain.com/blog/eeg-amplifier), Restricting duplicate values (https://stackoverflow.com/questions/73411332/how-to-dynamically-restrict-duplicated-value-of-input-text-in-a-looped-rand)
