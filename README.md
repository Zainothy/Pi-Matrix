# Pi-Matrix (WIP) 
In this application, the backend is written in python 3 and the frontend is in flutter. The app will use a library for Pi RGB Control: [rpi_ws281x](https://github.com/jgarff/rpi_ws281x) and a library for Python3 RGB animation: [BiblioPixel](https://github.com/ManiacalLabs/BiblioPixel), the goal is to have an app that can take pixel art inputs from an app with a fluid and intuitive UI, that can then send these instructions to a R-Pi that will apply the changes instructed to the grid of RGB light strips. 

## Decomposition of the task: 
Task Breakdown:

1. Research and Planning:

   ~a. **Identify RGB Library for Raspberry Pi:**~
      ~- Research and select a suitable RGB library compatible with Raspberry Pi.~
      ~- Consider factors such as community support, documentation, and ease of integration.~

   b. **Select App Development Framework:**
      - Choose Flutter for cross-platform mobile app development.
      - Assess compatibility with Raspberry Pi through the use of Python for backend integration.

2. Software Configuration:

   a. **Install and Configure RGB Library on Raspberry Pi:**
      - Follow the selected RGB library's documentation to install and configure it on the Raspberry Pi.

   b. **Develop Mobile App with Flutter:**
      - Use Flutter to create a mobile app for controlling LED strips.
      - Integrate Python on the Raspberry Pi as the backend for communication.

3. Hardware Setup:

   a. **Connect Raspberry Pi to LED Strips:**
      - Physically connect the Raspberry Pi to the LED strips using appropriate connectors.
      - Verify electrical compatibility and adhere to safety guidelines.

   b. **Soldering and Grid Setup:**
      - Solder the necessary connections between the Raspberry Pi and LED strips.
      - Set up the LED strips in a grid pattern according to the desired design.

4. Integration and Testing:

   a. **Test Communication Between App and Raspberry Pi:**
      - Ensure effective communication between the Flutter app and Raspberry Pi.
      - Verify that changes in the app are reflected in the LED strip's lighting patterns.

   b. **Test Pixel Art Display:**
      - Implement pixel art support within the Flutter app.
      - Confirm accurate display of pixel art designs on the LED strips.

5. Documentation:

   a. **Document Configuration Process:**
      - Create detailed documentation for both the software and hardware setup.
      - Include troubleshooting tips and common issues.

   b. **Provide User Guidelines:**
      - Develop user-friendly guidelines for using the Flutter app, uploading designs, and controlling the lights.

6. Finalization:

   a. **Optimization and Refinement:**
      - Fine-tune the system for optimal performance.
      - Address any remaining issues and optimize the software-hardware interaction.

   b. **Handover and Training:**
      - Present the completed lighting matrix system.
      - Provide training on operating and maintaining the system, emphasizing the use of the Flutter app for control.
