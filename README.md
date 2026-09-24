# CampusTracker

CampusTracker is a menu-driven Python application designed to help students efficiently manage their academic coursework, track hackathons/events, and analyze their overall workload.

## Features
* **Task & Event Management:** Add, update, search, and delete academic tasks and extracurricular events.
* **Smart Filtering:** Utilizes Python `Sets` to automatically filter and display unique subjects.
* **Workload Analytics:** Integrates **Pandas** for structured data formatting and **NumPy** to calculate total and average expected hours of work.
* **Data Persistence:** Uses File I/O to save records dynamically to text files (`tasks.txt` and `events.txt`).

## Technologies Used
* Python 3
* Pandas & NumPy
* Google Colab (for environment execution and Google Drive mounting)

## How to Run
This project is built to run in a Google Colab environment to bypass local strict IT execution policies.
1. Open `CAMPUS_TRACKER.ipynb` in Google Colab.
2. Run the notebook.
3. Grant permission to mount your Google Drive when prompted (this allows the program to safely generate and save the `.txt` data files to your personal drive).
4. Follow the on-screen menu prompts to interact with the tracker.

---
*Developed by JAGHATH SARVESH S (26MIS0239) for IACSE101.*
