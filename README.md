# **The Scourge: Shadow's Ascent**

**A Dark Fantasy Web Game of Chaos and Rebellion**

## **🖤 Project Overview**

**The Scourge: Shadow's Ascent** is a single-player, side-scrolling action game where the player assumes the role of a troubled **antihero** (referred to as **${charName}**) committed to destroying a corrupt world hierarchy known as the Golden Order.

The game is structured into three discrete levels, each ending with a powerful "Boss" representing the Order's corrupt authority. The core loop focuses on fast-paced platforming and projectile combat, with narrative progression delivered through dialogue scrolls during critical moments.

### **🔥 Game Features**

* **Dark Fantasy Theme:** A grim narrative centered on chaos, rebellion, and anti-heroism.  
* **Three Levels of Ascendancy:** Battle through The Garrison, the Sunken Archives, and the Zenith Spire.  
* **Scalable Architecture:** Built on a unified JavaScript stack, ensuring high performance and readiness for significant user growth.  
* **Persistent Scores:** Records the highest "Chaos Scores" globally using Firestore.

## **🛠 Tech Stack**

This project was built using a **single-language stack** (JavaScript) for rapid development and maximum compatibility, while leveraging Google's Firebase platform for immediate scalability.

| Component | Technology | Role |
| :---- | :---- | :---- |
| **Frontend** | HTML5 Canvas, Vanilla JavaScript | Game rendering, logic, and core mechanics. |
| **Styling/UI** | Tailwind CSS | Fast, dark-themed, and responsive interface design. |
| **Backend/DB** | Node.js (Conceptual), Cloud Firestore | Scalable, real-time persistence for the global **Chaos Leaderboard** (High Scores) and user state. |

## **▶️ Getting Started (Local Development)**

Since this is a single, self-contained HTML file, running the game is extremely simple.

### **Prerequisites**

You need a modern web browser (Chrome, Firefox, Edge, Safari).

### **Running the Game**

1. **Clone the repository:**  
   git clone \[YOUR\_REPO\_URL\]

2. **Navigate to the project folder:**  
   cd the-scourge-shadows-ascent

3. **Open the file:** Simply double-click index.html in your file explorer, or open it directly in your browser using the file path (e.g., file:///path/to/index.html).

The game will launch on the initial **Start Screen**, where you can name your character and begin your ascent.

## **🎮 Controls**

The controls are simple, prioritizing fluid movement and mouse/touch interaction for the main attack. Controls are confirmed after the initial Level 1 dialogue.

| Action | Desktop Keyboard | Desktop Mouse | Mobile Touch |
| :---- | :---- | :---- | :---- |
| **Move Left** | A or Left Arrow (\\u2190) | N/A | Left (\\u00ab) button |
| **Move Right** | D or Right Arrow (\\u2192) | N/A | Right (\\u00bb) button |
| **Jump** | W or Spacebar | N/A | Up (\\u21e7) button |
| **Attack (Chaos Bolt)** | N/A | **Left Mouse Button** | **💥 Attack** button (or anywhere on canvas) |
| **Pause Menu** | P key | PAUSE button | PAUSE button |

## **⚖️ Level Progression**

To advance from one level to the next, you must defeat **all** enemies currently on the screen, including the smaller minions and the final Boss.

### **Enemies of the Golden Order**

| Level | Boss | Minions |
| :---- | :---- | :---- |
| **1: The Garrison** | High Inquisitor | Ironclad Guard |
| **2: Sunken Archives** | Archivist of Truths | Archival Wraith |
| **3: Zenith Spire** | Solar Pontiff | Solar Zealot |

## **🎯 Future Scalability**

As requested, this project is built to scale. The use of a Node.js-friendly language (JavaScript) for both the client and server architecture means that if the game "takes off," the transition to a dedicated, high-concurrency backend using technologies like **Socket.IO** and **Node.js** for real-time multiplayer will be smooth, with minimal language context switching required.