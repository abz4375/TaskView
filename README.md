# TaskView: CPU Scheduling Algorithm Visualizer 🧠📊🚀

**Visualize and understand how different CPU scheduling algorithms work their magic!** ✨

This project lets you simulate and compare the performance of various CPU scheduling algorithms, helping you grasp the concepts behind these essential operating system components. 

## What is CPU Scheduling? 🤔

In a nutshell, CPU scheduling is like a traffic cop 👮 directing cars 🚗 at a busy intersection. It decides which process (the "car") gets to use the CPU (the "intersection") at any given time, aiming to keep things running smoothly and efficiently.

##  Algorithms Visualized 📈

This project brings to life the following algorithms:

- **FCFS (First-Come, First-Served):** Simple and fair – processes get CPU time in the order they arrive. 
- **SJF (Shortest Job First):** Favors shorter processes to reduce waiting times. 
    - **Preemptive:**  A shorter process can interrupt a longer one.
    - **Non-Preemptive:** Once a process gets the CPU, it runs to completion.
- **LJF (Longest Job First):**  The opposite of SJF, often used in batch systems.
    - **Preemptive:**  A longer process can interrupt a shorter one.
    - **Non-Preemptive:** Once a process gets the CPU, it runs to completion.
- **Priority:**  Each process has a priority level, and the CPU goes to the highest-priority process.
    - **Preemptive:**  A higher-priority process can interrupt a lower one.
    - **Non-Preemptive:**  A process runs to completion even if a higher-priority one arrives.
- **Round Robin:**  Gives each process a fixed time slice (quantum) and then cycles through them. 
- **Proposed:** A new algorithm that combines aspects of SJF, Round Robin, and Priority for potentially better performance. 

## Getting Started 🚀

1. **Open `index.html` in your web browser.**  🎉 You're in!
2. **Add Processes:** 
   - Click the "Add Process" button.
   - Enter the Burst Time (how long the process needs the CPU), Arrival Time (when it enters the system), and Priority.
   - Repeat for as many processes as you like!
3. **Choose Algorithms:** 
   - Use the dropdown menu on the "Evaluate" button to select which algorithms you want to compare.
4. **Run the Simulation:**
   - Hit that "Evaluate" button!  
5. **Analyze the Results:**
   - **Gantt Charts:**  Visualize how each algorithm schedules your processes over time.
   - **Result Table:** See calculated metrics like turnaround time, waiting time, response time, and more for each algorithm.
   - **"Best" Algorithm:** The project will suggest the most efficient algorithm based on the simulations! 🏆

## Explore and Learn 📚

- **Visualize Individual Algorithms:**  Use the "Visualize" dropdown button to focus on a single algorithm's execution step-by-step.
- **Edit or Remove Processes:** The "Edit Process" and "Remove Process" buttons give you control over your simulations.
- **Experiment!**  Try different process combinations, arrival times, and priorities to see how the algorithms perform in various scenarios.

## Happy Scheduling!  🥳
