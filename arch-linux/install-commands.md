# Install-commands
These are commands I have compiled from various sources such as Chris Titus Tech, Mental Outlaw, and the Arch Wiki.
The method of installation will be a section, and the commands listed in the order in which they are executed.

## archfi/archdi

- If you haven't already, set up internet. For wired connections, you should be good to go. For wireless networks, launch iwd: ```iwctl```
  - once in the iwd program, use the following to connect to your network: ```station (device, usually wlan0) connect (wifi ssid)```

- Now that you have internet, execute the following to get the latest package database: ```sudo pacman -Sy```

- Then enter this to download the archfi script: ```curl -LO archfi.sf.net/archfi```

- Launch the script: `sh archfi`