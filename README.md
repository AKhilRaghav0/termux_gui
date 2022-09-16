# Install Ubuntu20 on Termux Android

This installs Ubuntu 20 with xfce4 desktop on Termux. All scripts are from Andronix, I just compose and edit them to make the installer easier and smoother. It includes:

- [x] Ubuntu 20
- [x] XFCE4 Desktop
- [x] TigerVNC Server
- [x] Non-root Account Creation
- [x] Audio Support
- [x] Chromium Browser
- [] Camera Support
- [] KDE Desktop
## Installation

Copy and paste this command to Termux:

### Ubuntu 20 With XFCE4

```bash
pkg install wget curl proot tar -y && wget https://raw.githubusercontent.com/akhilraghav0/termux_gui/master/ubuntu.sh && chmod +x ubuntu.sh && bash ubuntu.sh
```

### Ubuntu 20 CLI Only

```bash
pkg install wget curl proot tar -y && wget https://raw.githubusercontent.com/akhilraghav0/termux_gui/master/ubuntu.sh && chmod +x ubuntu.sh && bash ubuntu.sh nde
```



## Run

### Start Ubuntu

After installation, on Termux, you can execute this command to run ubuntu or Create Bin dir in Home Folder:

```bash
./start-ubuntu20.sh
```

### Start VNC Server

On Ubuntu, run this command to start VNC Server:

```bash
vncserver-start
```

Then you can use VNC Client to connect to `127.0.0.1:1` or `127.0.0.1:5901` or `localhost:1`

### Stop VNC Server

On Ubuntu, run this command to stop VNC Server:

```bash
vncserver-stop
```

## VNC Client For Android

VNC Viewer (from RealVNC) is the best when you use your phone. Unfortunately, it does not does not support Samsung DEX.

[AVNC](https://f-droid.org/en/packages/com.gaurav.avnc/index.html) is another good VNC client.# termux_gui
# termux_gui
# termux_gui
# termux_gui
