# Hospital-Management-System

This Python code implements a basic Hospital Management System with a graphical user interface (GUI) using the tkinter library. Here's a breakdown of its functionalities:

# Classes:

## Patient: 
Stores patient information (name, age, gender, optional health issue).
## Doctor: 
Stores doctor information (name, department).
## Appointment: 
Stores appointment details (patient, doctor, date, time).
## Equipment (optional): 
Stores equipment information (name, quantity).
## Hospital: 
Manages the hospital system, including adding/removing patients, doctors, and appointments (optionally, equipment).
#Functions:

add_patient, add_doctor, schedule_appointment (placeholder): Core functions to manage patients, doctors, and appointments (implementation not shown for placeholder functions).
add_equipment (optional): Function to add equipment to the hospital (demonstrated in the code).
## GUI functions: 
Create separate windows for adding patients, scheduling appointments, viewing various lists (patients, doctors, appointments, equipment, optional: patient/doctor history). These functions handle user interaction with the GUI elements.
# Overall Structure:

## Imports: 
Includes necessary libraries (tkinter for GUI, optionally simpledialog for user input).
## Class Definitions: 
Defines the classes mentioned above.
## Hospital Instance: 
Creates an instance of the Hospital class with a name ("My Hospital" in this example). Optionally, pre-populates some doctors and patients.
## GUI Functions: 
Implements functions to create separate windows for various functionalities.
## Menu Bar: 
Creates a menu bar with options for managing patients, appointments, equipment (if implemented), viewing various lists, and accessing patient/doctor history.
## Main Window: 
Creates the main window with the title "Hospital Management System."
## Run the GUI: 
Starts the event loop (window.mainloop()) to handle user interactions with the GUI elements.
Note:

The code provides placeholder functions for some core functionalities and demonstrates adding equipment as an optional feature. You'll need to implement the missing functions to fully manage patients, doctors, and appointments.
