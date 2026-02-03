✅ Quick Tutorial: Install Ubuntu Server on VMware Workstation
Requirements

VMware Workstation installed

Ubuntu Server ISO (download from ubuntu.com)

At least 4 GB RAM (8 GB recommended)

20 GB free disk space

Step 1 — Create a New Virtual Machine

Open VMware Workstation.

Click Create a New Virtual Machine.

Select Typical (recommended) → click Next.

Choose Installer disc image file (ISO) and browse to your Ubuntu Server ISO.

Click Next.

Step 2 — Configure the Virtual Machine

Name: Ubuntu-Server

Location: Choose your preferred folder

Disk size:

Minimum: 20 GB

Select Store virtual disk as a single file for better performance.

Click Next → Finish.

👉 Optional (recommended):

Go to Edit virtual machine settings

Increase:

RAM: 4–8 GB

Processors: 2 CPUs

Step 3 — Start the Installation

Power on the virtual machine.

Select Install Ubuntu Server.

Choose your:

Language

Keyboard layout

Network settings (DHCP is fine for most setups)

Step 4 — Storage Configuration

Select Use an entire disk.

Confirm the changes.

The installer will automatically partition the disk.

Step 5 — Profile Setup

Enter:

Your name

Server name

Username

Strong password

👉 Enable OpenSSH if you want remote access (recommended).

Step 6 — Finish Installation

Wait for the installation to complete.

When prompted, reboot the VM.

Remove the ISO if VMware does not do it automatically.

✅ Done!

Log in with your username and password — your Ubuntu Server is ready.
