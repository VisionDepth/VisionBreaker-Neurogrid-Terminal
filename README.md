# VisionBreaker: Neurogrid Terminal

VisionBreaker: Neurogrid Terminal is a cyberpunk terminal toy and logic puzzle game built with Pygame.

You boot into a simulated grid, watch cascading code rain, and jack into a hidden puzzle layer. Solve terminal riddles to neutralize the TRACE system and unlock new visual themes as the Neurogrid bends to your will.

> Part ambient code rain visualizer, part minimal puzzle game.
> 
> Note: Contains flashing visuals, screen shake, and glitch effects. See Photosensitivity Warning below.

---
<p align="center">
  <img
    src="https://github.com/user-attachments/assets/9f2fd6b4-f085-444a-ac15-3ab9f8d46ecf"
    width="450"
    alt="VisionBreaker: Neurogrid Terminal – boot sequence"
  />
</p>

<p align="center">
  <img
    src="https://github.com/user-attachments/assets/fea784b8-a423-4940-9277-96eb7c2549d1"
    width="450"
    alt="Main Window"
  />
</p>

[![Downloads](https://img.shields.io/github/downloads/VisionDepth/VisionBreaker-Neurogrid/total?color=brightgreen)](https://github.com/VisionDepth/VisionBreaker-Neurogrid/releases)


## Features

### Dynamic Code Rain Engine
- High-density, resolution-adaptive code streams  
- Glowing trails, binary mode, occasional glitch flickers, and camera shake effects  
- Smooth fullscreen performance with optional slow-motion mode

### Neurogrid Boot Sequence
- Atmospheric diegetic startup screen  
- Type commands to “awaken” the terminal or abort the connection

### Interactive Hack Console
- Press `H` to open the **HACK>** prompt  
- Type any phrase to inject it directly into the falling code  
- Includes audio feedback for successful terminal submissions

### Puzzle Mode & TRACE System
- Press `P` to enter puzzle mode  
- Solve eight original Neurogrid-themed puzzles using the **HACK>** console  
- A rising TRACE bar increases pressure with:
  - Passive time gain  
  - Wrong answers  
  - Optional hint usage  
- Fully filled TRACE or multiple failures trigger a **critical system error**  
- Correct answers reset TRACE and advance to the next challenge

### Theme Unlock Progression
- Begin with a single visual theme  
- Each solved puzzle unlocks an additional color theme  
- Newly unlocked themes **auto-apply**, creating a dramatic visual shift  
- Special vertical “THEME UNLOCKED” rain celebrates each milestone

### Critical Error Events
- Intense red-tint overlay, glitch bars, camera shake, and a large **SYSTEM FAILURE** banner  
- Error sound effect and forced return to free mode  
- Designed to feel like a terminal meltdown without breaking gameplay

### Smart Hardware Behavior
- Launches in fullscreen at your display’s native resolution  
- Toggle between fullscreen and windowed mode at any time  
- Gracefully handles missing audio files without crashing

---

## Controls

### General
- **Esc**  
  - Close hack console  
  - Exit puzzle mode  
  - Quit the program (when not in console/puzzle)

- **F11**  
  Toggle fullscreen/windowed mode

- **Space**  
  Pause or resume the code rain animation  
  *(Critical error visuals and shake still animate while paused)*

---

### Visual & Rain Controls
- **C** – Cycle through unlocked color themes  
- **Up / Down Arrow** – Increase or decrease global rain speed  
- **B** – Toggle slow-motion mode  
- **N** – Toggle binary mode (`0` and `1` rain only)  
- **S** – Trigger a short manual camera shake  
- **E** – Trigger a critical system error on demand

---

### Hack Console
- **H** – Open the **HACK>** input line  
- **Enter** (while console is open)  
  - **Free mode:**  
    - Spawn your typed phrase as falling vertical text  
    - Play confirm sound  
    - Close console  
  - **Puzzle mode:**  
    - Submit your answer for the current puzzle

- **Backspace** – Delete last character  
- **Esc** – Cancel hack entry and close console

---

### Puzzle Mode & TRACE
- **P** – Enter puzzle mode from free mode

When puzzle mode is active:
- A dynamic **TRACE bar** appears (top-right)  
- The current **puzzle prompt** displays near the bottom  
- You reply exclusively through the **HACK>** console  
- Type **HINT** (and press Enter) to reveal a clue  
  - Hints cost TRACE, making them a strategic choice

Failure conditions:
- TRACE bar fills completely  
- Repeated incorrect answers

Success conditions:
- **Correct answers** show “ACCESS GRANTED,” reset TRACE, and move to the next puzzle  
- Completing all puzzles:
  - Neutralizes TRACE  
  - Unlocks all earned color themes  
  - Returns you to free mode


---


---

## Boot Screen

On launch you see a green boot sequence for the Neurogrid terminal.

- Wait for the boot lines to fully reveal
- The bottom of the screen will prompt you with a choice
- Type the required word and press Enter to jack in
- Or type the alternative word to close the program instead

This sequence is entirely text driven and fits the in universe lore for VisionBreaker.

---

## Requirements

- Python 3.9 or newer
- Pygame

## Installation

### If you like to try without using command prompts i have packaged the game into a .EXE 
- go to releases and choose the latest release and download the zip file
- once downloaded extract somewhere on Harddrive
- run the .exe 

You can run VisionBreaker: Neurogrid Terminal in a Conda environment (recommended) or with plain Python and `pip`.

### Option 1: Using Conda (recommended)

1. **Create a new environment**

   ```bash
   conda create -n VisionBreaker python=3.11
   ```

2. **Activate the environment**

   ```bash
   conda activate VisionBreaker
   ```

3. **Download the game**

   - Either clone the repo:

     ```bash
     git clone https://github.com/your-name/VisionBreaker-Neurogrid-main.git
     ```

   - Or download the ZIP from GitHub and extract it somewhere on your drive.

4. **Change into the project folder**

   ```bash
   cd path/to/VisionBreaker-Neurogrid-main
   ```

5. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

6. **Run the game**

   ```bash
   python VisionBreaker.py
   ```

---

### Option 2: Plain Python and pip

1. Make sure you have **Python 3.10+** installed and on your PATH.
2. Download or clone the repository and extract it.
3. Open a terminal in the project folder:

   ```bash
   cd path/to/VisionBreaker-Neurogrid-main
   ```

4. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Run the game:

   ```bash
   python VisionBreaker.py
   ```
---

## Photosensitivity Warning

This project contains:

- Rapidly changing visuals
- Flashing and strobing effects
- Screen shake and glitch effects
- High contrast color themes

These effects may trigger discomfort or seizures in people with photosensitive epilepsy or other light sensitivities.

If you experience dizziness, blurred vision, headache, nausea, or any kind of discomfort while playing, stop using the program immediately and rest. If symptoms persist, seek medical advice.

If you are prone to photosensitive seizures or visual migraines, you should talk to a medical professional before using this program or avoid it entirely.
