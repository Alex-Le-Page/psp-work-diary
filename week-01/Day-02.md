# Day 2 of Sprint Week

Today I finished any of my remaining changes to the CSV, however I may need to update them as the development process continues. After that I began to focus on the
procedural commentary of the car in the code. I did this first by downloading a python library (pyttsx3). This didn't work initially within the TORCS file due to the
TTS engine blocking the requests our code made to the car, so I had to create a new file called procedural_commentary.py that will run the engine and interpret the data
alongside the torcs_jm_par.py file running. This was made possible with a built in python library called "subrpocess". In order for the TTS to interpret car data in
real time, I decided to use a JSON file to share and update live data between the two files. Below is some snippets.

<img width="381" height="482" alt="image" src="https://github.com/user-attachments/assets/c49fc193-6edb-47c7-b26c-5e4ffc86bec1" />
<img width="563" height="747" alt="image" src="https://github.com/user-attachments/assets/9db893fc-84fb-4a89-8a58-89bda97c66b9" />

