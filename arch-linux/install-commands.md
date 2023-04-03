# Install-commands
These are commands I have compiled from various sources such as Chris Titus Tech, Mental Outlaw, and the Arch Wiki.
The method of installation will be a section, and the commands listed in the order in which they are executed.

## archfi/archdi

To get started, if you already have internet, enter ```$ curl -LO archfi.sf.net/archfi```

To get internet (such as if you use wifi), enter "iwctl" into the terminal:
  ```$ iwctl```

Once in the new prompt, use the following to connect to your wifi network: ```[iwctl]# station (device) connect (Wifi SSID)```

If your wifi requires a passphrase, it will ask you for it.