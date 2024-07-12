# Traffic Light Program on Beckhoff Platform

## Objective
Create a traffic light control program using Beckhoff TwinCAT 3.

## Requirements
- **Traffic Lights Control:**
  - Control 2 sets of traffic lights (4 total) with three states: Red, Yellow, and Green.
  - Each light should follow a standard traffic light sequence.
- **Pedestrian Crossing:**
  - Implement 1 pedestrian crossing button that changes the light sequence to allow safe crossing for one direction only.
  - After a 15-second crossing time, the lights should return to the previous orientation.

## Evaluation Criteria
- **Code Quality and Readability:**
  - Ensure the code is clean, well-documented, and easy to read.
- **Correctness of the Traffic Light Sequence:**
  - The traffic light sequence must be accurate and follow the standard pattern.
- **Handling of Edge Cases:**
  - Address scenarios such as simultaneous pedestrian button presses.
- **Presentation:**
  - Be prepared to explain the code and logic during a brief presentation.

## Timeline (Estimates)
- **Basic PLC Code for Traffic Light Function:** 2 hours
- **Basic HMI Design for Lights and Buttons:** 2 hours
- **Testing and Troubleshooting:** 2 hours

## Resources
- Use the provided VM with Beckhoff installed (provided by the team).

## Setup Instructions
1. **Install Beckhoff TwinCAT 3:**
   - Ensure Beckhoff TwinCAT 3 is installed on your machine. Use the provided VM if necessary.
   
2. **Project Structure:**
   - Create a new project in TwinCAT 3.
   - Organize your code into sections for traffic light control, pedestrian crossing logic, and HMI design.

3. **Traffic Light Control Logic:**
   - Implement the standard traffic light sequence for two sets of traffic lights.
   - Ensure transitions between Red, Yellow, and Green states are smooth and timely.

4. **Pedestrian Crossing Logic:**
   - Integrate the pedestrian crossing button.
   - Implement the logic to change the light sequence when the button is pressed.
   - Ensure a 15-second crossing time and then revert to the previous light orientation.

5. **Human-Machine Interface (HMI):**
   - Design a simple HMI to visualize the traffic lights and pedestrian button.
   - Ensure the HMI is user-friendly and accurately represents the traffic light states.

6. **Testing and Troubleshooting:**
   - Test the traffic light sequence thoroughly.
   - Simulate edge cases, such as simultaneous pedestrian button presses, to ensure robust handling.
   - Debug any issues and refine the code for optimal performance.

7. **Presentation Preparation:**
   - Be ready to explain your code, logic, and design choices during a brief presentation.
   - Highlight how edge cases are handled and the overall flow of the program.

## Contributing
Feel free to fork this repository, create a new branch, and submit pull requests for improvements or bug fixes.

---

**Note:** The provided VM with Beckhoff installed will be available for your use. Feel free to utilize this resource to streamline the development process.
