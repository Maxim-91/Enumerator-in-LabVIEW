# Enumerator in LabVIEW

This LabVIEW project demonstrates the usage of enumerator (enum) data types in an event-driven program. It provides an interface to handle user interactions by changing the enum control and displays corresponding messages based on the selected enum value.

## Overview

The program consists of an event structure that handles specific value changes in enumerator controls (`01`, `02`, `03`, `04`, `05`, and `stop`). Depending on the selected value in the enumerator, the program outputs corresponding messages to indicate which option has been chosen.

## Features

1. **Event-Driven Enumerator Handling**
   - The program uses an event structure to listen for value changes in the enumerator controls and responds with appropriate string outputs.

2. **Event Cases and Corresponding Actions**
   - **Timeout Event:**
     - When no user interaction occurs for a specified time, the program triggers the `Default` event, setting the output string to `"Default"`.

   - **"01" Value Change Event:**
     - When the enum control labeled `"01"` is selected, the output string displays `"Один"`.

   - **"02" Value Change Event:**
     - Selecting `"02"` updates the output string to `"Два"`.

   - **"03" Value Change Event:**
     - Choosing `"03"` sets the output string to `"Три"`.

   - **"04" Value Change Event:**
     - Selecting `"04"` results in the string output `"04"`.

   - **"05" Value Change Event:**
     - Choosing `"05"` sets the output string to `"05"`.

   - **"stop" Value Change Event:**
     - When the `"stop"` option is selected, the program outputs the string `"Стоп"` and stops the operation.

## How It Works

- **Event Structure**:  
  The event structure waits for changes in the enumerator controls and handles each value change by updating the output string. This allows users to see real-time changes based on their selection.

- **String Outputs**:  
  Each event case corresponds to a unique output string, which is displayed as the control value is updated.

## Usage

- Run the VI and interact with the enumerator controls (`01`, `02`, `03`, `04`, `05`, and `stop`).
- Observe how selecting each value results in a corresponding text output on the string indicator.
- Choose `"stop"` to end the program.

## Requirements

- LabVIEW software is required to open and run the VI.

## Code
![image](https://github.com/user-attachments/assets/d08e7ad2-8d6f-4fa3-87eb-ded5f42a8b77) 
![image](https://github.com/user-attachments/assets/261d0559-eefc-427a-9089-03b2a6365b32) 
![image](https://github.com/user-attachments/assets/138f2d18-378e-44b9-b61f-49d06179a7fe) 
![image](https://github.com/user-attachments/assets/5758b027-6c7d-4bbf-9651-8e3cac08dbba) 
![image](https://github.com/user-attachments/assets/2535d9b9-c1b4-402a-a765-1f1b28453e46) 
![image](https://github.com/user-attachments/assets/98e4b645-6cd3-4924-b99b-2faefb2e7209) 
![image](https://github.com/user-attachments/assets/055f2493-1aa7-4a3d-a67c-ae3cfe3da312) 

## The appearance of the program
![image](https://github.com/user-attachments/assets/6b7b42f0-d8ea-4889-8c34-86b0b4f8ccd4) 
![image](https://github.com/user-attachments/assets/0d8766b2-0b39-40d5-a25e-d73c29a22754)
