# Smart-Car-Parking-System
In commercial areas there are no open parking spaces available and finding an empty parking space after entering a large parking lot are the two major issues which are addressed.

PROBLEM STATEMENT:

Finding a parking space in most metropolitan areas, especially during the rush hours, is difficult for drivers. Difficulty arises from not knowing where the available spaces, may be at that time traffic congestion may occur. Traditional parking systems often lack real-time data and intelligent management capabilities, resulting in inefficient utilization of parking resources. Even the drivers get frustrated due to this which is leading to time-consuming searches for parking spots. Therefore, there is a pressing need for the development of innovative IoT-enabled car parking systems to revolutionize urban mobility.

MOTIVATION:

With growing urbanization and increasing vehicle ownership, traditional parking systems are   becoming inefficient, leading to congestion, wasted time, and frustrated drivers. By leveraging Arduino and IoT technologies, we aim to revolutionize parking management, optimize space utilization, reduce congestion, and enhance user experience. This system seeks to offer a solution that not only addresses current parking challenges but also prepares cities for future mobility needs in a sustainable and efficient manner. And thus, the title “Smart Car Parking System.” This project really sounded interesting because of the development of this system using IoT technology and it is motivated by a shared vision of a future where cities are vibrant, inclusive, and sustainable and to have an organised cities which are environmentally responsible.

PROPOSED SOLUTION:

The solution that is feasible for this problem is implementing an IoT based Smart Car Parking System. This smart parking system project consists of Arduino uno, two servo motor, one LCD display, and four IR sensors. Where the Arduino is the main microcontroller that controls the whole system. Two IR sensors are used at the entry and exit gates to detect vehicle entry and exit in the parking area. The parking slot availability is detected by other four IR sensors. The servo motor is placed at the entry and exit gate that is used to open and close the gates. When a vehicle arrives at the entry gate of the parking area it is detected by IR sensor and if there are any empty slots then the system opens the entry gate by the servo motor. After entering the car into the parking area, when it will occupy a slot, then is displayed in the mobile app. Similarly, when a car arrives at the exit gate it is detected by IR sensor the gate is opened by servo motor. 
The user needs to check the availability of the slots through LCD display. In the LCD display, if a particular slot is occupied then the status of the slot is displayed as 1 otherwise it remains 0. 

FUNCTIONAL MODULES:

Arduino: Arduino, a versatile microcontroller platform, serves as the brain of the parking system. It processes sensor data, controls servo motors, and manages LED displays based on predefined algorithms and user inputs.

IR Sensors: Infrared (IR) sensors play a crucial role in detecting the presence of vehicles within parking spaces. Strategically placed sensors accurately identify vacant and occupied slots, providing real-time occupancy information to the control unit.

Servo Motors: Servo motors actuate the physical barriers or gates within the parking facility. They are responsible for opening and closing parking slots in response to commands from the control unit, ensuring smooth vehicle entry and exit.

LCD Display: LCD displays serve as visual indicators for drivers, guiding them to available parking spaces. The displays convey essential information such as parking availability, slot numbers, and directional cues, enhancing user experience and efficiency.
