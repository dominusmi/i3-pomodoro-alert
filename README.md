# I3 Pomodoro break alert
Small bash script to display a pomodoro break alert every x minutes.
## Installation
1. Donwload the pomodoro-alert script and put it into the `/usr/local/sbin` folder.
2. Make the file executable: `chmod +x /usr/local/sbin/pomodor-alert`
3. Run `crontab -e` in your terminal, and add the following line at the end of the file, replacing `x` with the number of interval you want (e.g. `*/35` for alert every 35 minutes)
`*/x * * * * /usr/local/sbin/pomodoro-alert`

