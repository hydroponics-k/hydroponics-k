The goal of this bachelor thesis project is to create an automated system to monitor and manage a hydroponic nutrient film technique system.
It is split into 3 different components that aim to achieve the following possibilities:
- Microcontroller NodeMCU ESP8266
    - Monitor water level of reservoir, nutrients, pH-value and temperature of water, room temperature and humidity as well as status of lighting
    - Control waterpumps for irrigation, dosing pumps to add nutrients, adjust pH-value and lighting
- Raspberry Pi Zero W
    - Take pictures of plants over time with NoIR camera
    - Evaluate plant growth over time
- Raspberry Pi 3 A+ as server that
    - hosts a website where sensor data is displayed
    - allows configuration of microcontroller setup
    - displays warnings if plant growth is in decline
    - adjusts nutrient settings according to plant growth
