# Virtual-Pet-Simulator
Developed an interactive virtual pet dog application using java swing and modular programming implemented realistic pet behaviours -eating, sleeping, playing - using object -oriented principles


🎮 Overview

The Virtual Pet Simulator allows players to adopt and care for a virtual pet. The pet has dynamic attributes like Hunger, Happiness, and Health, which change over time and based on the player's actions.
Your goal is to keep your pet happy, healthy, and alive as long as possible!

🧩 Features

✅ Interactive GUI:
Built with Java Swing, providing buttons and text areas for user interaction.

✅ Real-Time Simulation:
A background timer simulates the passage of time, aging your pet every second.

✅ Pet Actions:
You can:

🍗 Feed your pet to reduce hunger and slightly increase happiness.

🎾 Play with your pet to increase happiness but make it hungrier.

💊 Heal your pet to restore health to full.

🔍 Check Status anytime to see current stats.

🚪 Exit the simulator safely.

✅ Dynamic Pet Life Cycle:
Your pet’s hunger, happiness, and health fluctuate naturally:

Ignoring your pet increases hunger and decreases happiness.

If hunger gets too high or happiness too low, health begins to drop.

When health reaches zero, your pet unfortunately passes away.

💻 Technologies Used

Language: Java

GUI Framework: Java Swing

Concepts: Object-Oriented Programming (OOP), Event Handling, Timers, UI Layout Management

🧠 Key Concepts Demonstrated

Encapsulation: Pet attributes (hunger, happiness, health) are managed within the Pet class.

Event Handling: Button clicks trigger specific pet actions.

Timers & Simulation: A javax.swing.Timer automates time progression.

Modular Design: GUI logic and simulation logic are separated for clarity.

🏗️ Project Structure
VirtualPetSimulator/
│
├── Pet.java                # Class representing the virtual pet's behavior and attributes
├── VirtualPetSimulator.java # Main GUI class managing user interaction and the simulation
└── README.md               # Project documentation


Open the Project:

Use any Java IDE (e.g., IntelliJ IDEA, Eclipse, NetBeans) or compile from terminal.

Compile and Run:

javac VirtualPetSimulator.java
java VirtualPetSimulator


Enjoy!
Give your pet a name and start taking care of it 🐶🐱.

🖼️ Screenshots

(Optional: Add screenshots of your running app, showing the interface and pet status panel.)

🧾 Example Gameplay

Enter a pet name (e.g., “Buddy”).

Watch your pet’s stats update in real-time.

Feed, play, or heal as needed to keep it alive.

Be careful — neglecting your pet can cause it to lose health and eventually pass away. 😢

🧰 Future Improvements

Add multiple pet types with different behavior patterns.

Implement saving and loading pet progress.

Include animations or sprites for visual appeal.

Add sound effects for interaction feedback.

💡 Purpose

This project is ideal for:

Beginners learning Java GUI programming.

Students exploring object-oriented design and event-driven programming.

Developers looking to build small simulation games.
