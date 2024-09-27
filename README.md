# Bash Scripting Programs
This repository contains five simple yet useful programs written in Bash to practice and demonstrate basic scripting skills. These scripts are beginner-friendly and cover a range of operations such as user interaction, countdowns, random number generation, and running multiple scripts together.
## Table of Contents
1. [Programs Overview](#programs-overview)
2. [How to Use](#how-to-use)
3. [Requirements](#requirements)
4. [Program Descriptions](#program-descriptions)
## Programs Overview
This repository consists of the following Bash scripts:
1. [questionnaire.sh](/questionnaire.sh): Interactively asks the user for their name, location, and favorite coding website, then provides a customized response.
2. [countdown.sh](/countdown.sh): Takes a positive integer as an argument and counts down to zero with a 1-second delay between numbers.
3. [bingo.sh](/bingo.sh): Generates a random Bingo number (between 1 and 75) and announces the corresponding Bingo column (B, I, N, G, O).
4. [fortune.sh](/fortune.sh): Acts as a fortune teller by giving random responses to a yes/no question provided by the user.
5. [five.sh](/five.sh): A meta-script that runs all four of the above scripts in sequence.
## How to Use
1. Clone the repository:<br>
   git clone https://github.com/na-ahmed/Programs-using-Bash-scripting.git
2. Navigate to the repository directory:<br>
   cd Programs-using-Bash-scripting
3. Make the scripts executable:<br>
   chmod +x *.sh
4. Run any of the individual scripts:<br>
   ./questionnaire.sh<br>
   ./countdown.sh<br>
   ./bingo.sh<br>
   ./fortune.sh<br>
5. Alternatively, you can run all scripts at once using:<br>
   ./five.sh
