
<p align="center">
  <img src="./img.png" alt="ZenLock Detox Banner" width="100%">
</p>

# ZENLOCK DETOX

---

## Basic Details

### Team Name

DAMASCUS

### Team Members

* Ann Maria Martin – Model Engineering College, Thrikkakkara
* Irene Sara Sam – Model Engineering College, Thrikkakkara

### Hosted Project Link

https://zenlock.vercel.app/

### Project Description

ZenLock Detox is a web-based mindful intervention platform designed to interrupt doomscrolling behavior and promote intentional digital usage. When users activate the Digital Pause feature, the system initiates a structured 60-second cognitive reset experience using guided breathing and interactive engagement.

### The Problem Statement

Excessive passive scrolling on social media platforms contributes to reduced attention span, anxiety, and digital dependency. Users often lack immediate mechanisms to interrupt compulsive scrolling patterns once they begin.

### The Solution

ZenLock Detox introduces a single-click digital pause system that temporarily locks the interface and engages users in a structured mindfulness intervention. Through guided breathing, interactive canvas engagement, and habit tracking, the platform transforms passive scrolling into a conscious reset moment.

---

## Technical Details

### Technologies/Components Used

**For Software:**

* Languages used: HTML5, CSS3, JavaScript (Vanilla JS)
* Frameworks used: None (Lightweight client-side architecture)
* Libraries used:

  * Lucide Icons (CDN)
  * Canvas Confetti (CDN)
* Tools used:

  * Visual Studio Code
  * Git & GitHub
  * Browser Developer Tools

**For Hardware:**
Not applicable (Web-based project)

---

## Features

* **Digital Pause Trigger:** One-click activation of a 60-second mindful intervention.
* **Guided Breathing System:** Visual inhale/exhale pacing to regulate focus and calm the nervous system.
* **Interactive Doodle Canvas:** Full-screen canvas for grounding interaction during the intervention phase.
* **Streak Tracking System:** Persistent habit tracking using LocalStorage to encourage consistent usage.
* **Offline Capability:** Can function offline once loaded (PWA-enabled version).

---

## Implementation

### For Software:

#### Installation

```bash
# Clone the repository
git clone https://github.com/annmmartin2237/Zenlock.git

# Navigate to project directory
cd zenlock-detox
```

#### Run

This is a client-side project and must be served using a local server.

Option 1 – Using VS Code Live Server:

* Install the Live Server extension
* Right-click index.html
* Select “Open with Live Server”

Option 2 – Using Python:

```bash
python -m http.server 5500
```

Then open:

```
http://localhost:5500
```

---

## Project Documentation

### Screenshots

<img width="1920" height="1080" alt="Screenshot (2)" src="https://github.com/user-attachments/assets/640512b4-d61e-40bf-9023-86e80834de4e" />

*Main dashboard interface with Digital Pause trigger.*

<img width="1920" height="1080" alt="Screenshot (5)" src="https://github.com/user-attachments/assets/f66e4696-4835-4585-aab8-e8bd44add9a6" />

*Active 60-second guided breathing and doodle canvas screen.*

<img width="1920" height="1080" alt="Screenshot (6)" src="https://github.com/user-attachments/assets/8c3e817c-8ec6-42e6-8faf-034fa653f68d" />

*Streak and habit tracking interface displaying progress.*

---

### Diagrams

**System Architecture:**

![Architecture Diagram](<img width="1024" height="559" alt="image" src="https://github.com/user-attachments/assets/215b44e1-c9d8-45a4-be60-289a0076fccf" />
)
*User triggers intervention → Timer & Breathing Engine activates → Canvas interaction → Streak system updates via LocalStorage → Return to dashboard.*

**Application Workflow:**

*User Action → Lock Interface → Mindfulness Intervention → Completion → Progress Update → Exit to Home Screen.*

---

## Additional Documentation

### Architecture Overview

The system follows a client-side modular structure:

* UI Layer – Handles layout and interactions
* Intervention Engine – Controls timer and breathing cycle logic
* Canvas Module – Manages interactive doodling
* Persistence Layer – Stores streak data using LocalStorage

No backend or database is required.

---



### Additional Demo

Live Website: https://zenlock.vercel.app/

---

## AI Tools Used (For Transparency)

**Tool Used:** ChatGPT

**Purpose:**

* Code optimization
* Debugging assistance
* Documentation formatting
* Architectural planning suggestions

**Estimated AI Contribution:** Approximately 20–30% (assistance and refinement only)

**Human Contributions:**

* Core idea and concept design
* UI/UX decisions
* Feature logic implementation
* Integration and testing

---

## Team Contributions

* Ann Maria Martin: Concept ideation, frontend development, intervention logic, documentation
* Irene Sara Sam: UI styling, testing, deployment, debugging support

---

## License

This project is licensed under the MIT License – see the LICENSE file for details.

---

Made at TinkerHub Hackathon
