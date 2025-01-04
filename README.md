# To run the script, you need to have root privileges.  
## Download and cd into the directory of the script, use sudo to run the script;

# Default configuration

Run ` sudo ./iwlwifi-configurer.sh `

If no option is provided, the script will default to using the -d option (default configuration).

# Custom Configuration

Run ` sudo ./iwlwifi-configurer.sh -c `

you will be able to set custom settings for the parameters this script changes- via a input dialog.

# Backups

If ` /etc/modprobe.d/iwlwifi.conf ` exists, a backup is created at ` ~/iwlwifi-config/iwlwifi.conf.bak `

- - - - - - - -
This is a pretty janky script, but it works for my needs. Feel free to do whatever you want with it.
