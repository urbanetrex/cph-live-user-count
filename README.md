# CPH Live User Count *\*and plotting\**

## How To Use
### Preparations
Ensure you have:
- VS Code
- A Python3 interpreter
### Download
- If you have a GitHub Account, then downloading GitHub Desktop is great. Clone or fork this repo and download it somewhere on your computer.
- If not, you need to create a `cph-live-user-count` folder on your computer and create two files `plotting.py` and `watch_pool.py`, then copy the raw info from here to the two files. Make sure you copy the right information to the right file.
### Use
- Open the `cph-live-user-count` folder in VS Code. Follow the instructions on top of the files. Open **two** Terminal tabs or windows. Have you ensured `matplotlib`, `pandas`, `requests` are installed? If not, run the commands shown in the files to install them.
- Now run `python3 watch_pool.py` (or `caffeinate -dims python3 watch_pool.py` if you want more continous running). A `pool_log.csv` will be generated. Keep it.
- When you want to show plots, run `python3 plotitng.py`. A plot will be generated from the CSV in a few seconds (or minutes, depending on how long you monitored).
