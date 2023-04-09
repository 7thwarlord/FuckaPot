# HoneygainAutoClaim

HoneygainAutoClaim is a simple [Python](https://www.python.org/) script that **automatically claims your daily bonus** from [Honeygain](https://r.honeygain.me/ROSCH76C7D). Honeygain is a 
service that allows you to earn **passive income** by **sharing** your **internet** connection with others.


## Requirements
- [Python 3](https://www.python.org/downloads/)


## Usage
- **Clone** or **download** this repository. 
- Install the **required** modules with 
```commandline 
pip install -r requirements.txt
```  
- Run the script with 
```commandline
python3 /absolut folder path/main.py
```
- [Create a schedule](#Create-a-schedule) to run the program every day.
- Enjoy your **daily bonus**!


## Disclaimer
This script is **not** affiliated with or endorsed by Honeygain. Use it at your **own risk** and responsibility. The **author** is **not responsible** for any consequences that may arise from using this script.

### Create a schedule

#### Linux

1. ```commandline
   crontab -e
   ```
2. Add this line at the **bottom** `0 8 * * * python3 /absolut folder path/main.py` to run the script every day at 8:00 am.

#### Windows

1. Open the `Task Scheduler`
2. Create a new **basic Task**
3. Give the task a **name**
4. Choose a **daily trigger**
5. Select the **time**, when to run it
6. Select as action to **start a program**
7. Select the path to the **main.py**