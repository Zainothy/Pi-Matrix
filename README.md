# Pi-Matrix (WIP) 
In this application, the backend is written in python 3 and the frontend is in flutter. The app will use a library for Pi RGB Control: [rpi_ws281x](https://github.com/jgarff/rpi_ws281x) and a library for Python3 RGB animation: [BiblioPixel](https://github.com/ManiacalLabs/BiblioPixel), the goal is to have an app that can take pixel art inputs from an app with a fluid and intuitive UI, that can then send these instructions to a R-Pi that will apply the changes instructed to the grid of RGB light strips. 

## Decomposition of the task: 
### 1. Research and Planning:

   ~a. **Identify RGB Library for Raspberry Pi:**
      - Research and select a suitable RGB library compatible with Raspberry Pi.
      - Consider factors such as community support, documentation, and ease of integration.~

   b. **Select OSS App for Raspberry Pi Control:**
      - Explore open-source applications compatible with Raspberry Pi for controlling LED strips.
      - Evaluate the features, user interface, and community feedback of potential apps.

### 2. Software Configuration:

   a. **Install and Configure RGB Library on Raspberry Pi:**
      - Follow the library's documentation to install and configure it on the Raspberry Pi.

   b. **Configure OSS App for Pixel Art Support:**
      - Customize the selected app to support pixel art or find an existing plugin or feature for this purpose.
      - Ensure the app can upload and display designs on the LED strips.

### 3. Hardware Setup:

   a. **Connect Raspberry Pi to LED Strips:**
      - Physically connect the Raspberry Pi to the LED strips using appropriate connectors.
      - Verify the electrical compatibility and follow safety guidelines.

   b. **Soldering and Grid Setup:**
      - Solder the necessary connections between the Raspberry Pi and LED strips.
      - Set up the LED strips in a grid pattern as per the desired design.

### 4. Integration and Testing:

   a. **Test Communication Between App and Raspberry Pi:**
      - Ensure the app can communicate with the Raspberry Pi effectively.
      - Verify that changes in the app are reflected in the LED strip's lighting patterns.

   b. **Test Pixel Art Display:**
      - Upload pixel art designs using the app and confirm they are accurately displayed on the LED strips.

### 5. Documentation:

   a. **Document the Configuration Process:**
      - Create detailed documentation outlining the steps for configuring both the software and hardware components.
      - Include troubleshooting tips and common issues.

   b. **Provide User Guidelines:**
      - Develop user-friendly guidelines for Krispin on how to use the app, upload designs, and control the lights.

### 6. Finalization:

   a. **Optimization and Refinement:**
      - Fine-tune the system for optimal performance.
      - Address any remaining issues and optimize the software-hardware interaction.
