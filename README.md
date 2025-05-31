# Password-Based Door Unlocking System

This project is an embedded system titled **"Password-Based Door Unlocking System"**. It is designed to enhance security by allowing access only when the correct password is entered. The system is implemented in C++ and is ideal for educational purposes, home automation, and embedded system enthusiasts.

## Demo Video

You can watch a demonstration of the system here:

<video src="https://github.com/Mkaify/Password-Based_DoorUnlockingSystem/raw/main/ESPVideo.mp4" controls width="480"></video>

Alternatively, [download or view the video directly](https://github.com/Mkaify/Password-Based_DoorUnlockingSystem/raw/main/ESPVideo.mp4).

## Features

- Password-based authentication for door unlocking
- Simple and user-friendly interface
- Secure access control using microcontroller logic
- Easy to customize the password in code

## Getting Started

### Prerequisites

- Microcontroller (e.g., Arduino, AVR, etc.)
- Keypad for password input
- Servo motor or relay to control door lock
- LCD display (optional, for user feedback)
- Basic electronic components (resistors, wires, breadboard, etc.)
- C++ compiler or Arduino IDE

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Mkaify/Password-Based_DoorUnlockingSystem.git
   ```
2. Open the code in your preferred IDE (e.g., Arduino IDE for Arduino-based systems).
3. Connect the hardware components according to your microcontroller’s pin configuration.

### Usage

1. Upload the C++ code to your microcontroller.
2. Power up the system.
3. Enter the predefined password using the keypad.
4. If the password is correct, the door will unlock (servo/relay will activate).
5. If the password is incorrect, access will be denied.

## Customization

- You can change the password by editing the relevant variable in the source code.
- Modify pin assignments as needed to match your hardware setup.

## Project Structure

- `main.cpp`: Core logic for password input and door control
- `README.md`: Project documentation (this file)
- Other supporting source and header files as needed

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Inspired by embedded systems security projects and home automation solutions

---

For any questions or suggestions, please open an issue or contact the project owner.
