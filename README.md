# OS CPU Scheduling 
Interactive FCFS CPU Scheduling Visualizer using Java Swing — simulates process execution as a Boss Fight Arena game with real-time animation, timers, and performance metrics.

# FCFS CPU Scheduling Visualizer – Boss Fight Arena Game

A **fun and interactive visualizer** for the **First Come First Serve (FCFS)** CPU Scheduling algorithm — themed as a **Boss Fight Arena** game!  
Built using **Java Swing (AWT + Swing GUI)**, this project visually demonstrates how FCFS scheduling works by animating processes (players) as they move from the **Ready Queue (Lobby)** to the **CPU (Boss Fight)** and finally to the **Completed Queue (Winners List)**.

---

## Project Overview

This visualizer simulates how the **First Come First Serve (FCFS)** scheduling algorithm executes processes based on their **arrival time**.

Each process (player) arrives, fights the boss for its **burst time**, and then moves to the completed area when done.  
A **live time counter** updates to show the **CPU time progress**, and once the simulation ends, a **results table** displays:

- Completion Time (CT)  
- Turnaround Time (TAT)  
- Waiting Time (WT)  
- Response Time (RT)  
- Average TAT and WT

---

## ⚙️ Features

Visual animation of FCFS scheduling  
Interactive GUI using **Java Swing**  
Real-time CPU timer  
Automatic computation of CT, TAT, WT, RT  
Color-coded processes for clarity  
End-of-simulation summary table  
Simple "Start Fight" button to begin simulation  

---

## Themed Design

The program is themed as a **game**:

| FCFS Concept | Game Analogy |
|---------------|---------------|
| Process | Player |
| CPU | Boss Fight Arena |
| Ready Queue | Lobby |
| Completed Queue | Winners List |

---

## Process Details (Default Data)

| Player (Process) | Arrival Time | Burst Time | Color |
|------------------|---------------|-------------|--------|
| Knight_Peter     | 0             | 3           | Pink   |
| Archer_John      | 1             | 5           | Orange |
| Warrior_Mike     | 2             | 2           | Green  |
| Fighter_Tom      | 3             | 4           | Cyan   |

---

## Tech Stack

- **Language:** Java  
- **GUI Framework:** Swing / AWT  
- **IDE (Recommended):** IntelliJ IDEA, Eclipse, or NetBeans  

---

## How to Run

1. Clone this repository:
   ```bash
   https://github.com/Arjun-jpeg/CPUscheduling.git

2.Open the project in your preferred Java IDE (such as IntelliJ IDEA, Eclipse, or NetBeans)

3.Compile and run the main file: FCFSVisualizer.java

4.Click on “Start Fight” in the application window to begin the FCFS simulation
   

