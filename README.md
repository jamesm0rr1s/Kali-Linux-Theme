# Kali Linux Theme

Kali Linux Theme is a script that customizes Kali Linux 2020+ for penetration testing and red teaming.

## Main Features

 - The terminal prompt is set to show the name, date, time, path, and if the UID is 0
 - Windows will gain focus on hover
 - The click policy is set to open files and directories with a single click
 - Executable files will be displayed in a text editor when clicked
 - The clock is set to show the date and time
 - The top panel is personalized with favorite apps
 - The alias/command "renet" is added which will restart networking and print out the external and internal IP addresses
 - The hostname is updated
 - The background is updated

## Installation

Clone the GitHub repository
```
sudo git clone https://github.com/jamesm0rr1s/Kali-Linux-Theme /opt/jamesm0rr1s/Kali-Linux-Theme
```

## Usage

Run the following commands:
```
sudo chmod +x /opt/jamesm0rr1s/Kali-Linux-Theme/kali-linux-theme.sh
sudo -E bash /opt/jamesm0rr1s/Kali-Linux-Theme/kali-linux-theme.sh kali
```

## Custom Commands

Restart networking and print the external and internal IP addresses
```
renet
```

Turn hover to focus on
```
hover-on
```

Turn hover to focus off
```
hover-off
```