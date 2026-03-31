# CIVE202-Project3-Group12
  Transportation systems are crucial for the economy and daily life. To support informed decision-making, the United States invests heavily in collecting extensive data to understand transportation usage. Highly influential datasets in this field are the National Household Travel Survey (NHTS) and the Next Generation Simulation (NGSIM) Data.  

---
## Repository Structure

- [Raw_NGSIM_data](NGSIM.csv)
- [Raw_NHTS_data](NHTS.csv)
- [Notebook(Project_3_Code)](CIVE202_Spring2026_Project3_Group12_Code.ipynb)

---
## User Guide

### 1. Program Overview
  This program creates clean and simple visualizations of the important features and trends in the data. The following visualizations are present: A bar chart, histogram, box plot, and three line plots. The program also provides a simulation study using the Intelligent Driver Model (IDM), to visualize and simulate vehicle behavior and vehicle trajectories. Our team organized and visualized the NGSIM and NHTS data to understand transportation usage and system performance.

**Example:**
The methods below will go through one of the visualizations used in our team's code, which is a lineplot. 

### 2. Units
- Time = seconds (s)
- Acceleration = (m/s)
- Position (m)

### 3. Methods
1. Set the trajectory number by assigning it. The code will look like this: "trajectory_number = 4". This indicates the vehicle pair.
2. Plot the figure using the "plt.figure" function and set the figure size.
3. Using the "sns.lineplot" command, set your x and y variables and enter in the correct dataset for the leader and follower speed. Leader speed will look like this: "sns.lineplot(x = data_subset['Time'], y = data_subset['leader_speed(m/s)'], label = 'Leader Speed')". The next line will replace the word 'leader' with 'follower'.
4. Assign the x and y labels, title, and legend using the "plt." function. Make sure to assign font sizes as well.
5. Once the above steps are completed, show the plot with the "plt.show" command.

---
## Project Goals
The goals of this project were outlined with the use of a Gantt Chart. The link is here:

- [Gantt_Chart](CIVE202_Spring2026_Project3_Group12_GanttChart.xlsx)

---
## Project Documentation
`Links:`

- [Scope_of_Work](CIVE202_Spring2026_Project3_Group12_SOW.docx)
- [Written_Report](CIVE202_Spring2026_Group12_Project3_WrittenReport.docx)
- [Engineering_Time_Sheet](CIVE202_Spring2026_Project3_Group12_EngineeringTimeSheet.csv)
- [Annotated_Code_Document](CIVE202_Spring2026_P3_Group12_ACD.xlsx)
