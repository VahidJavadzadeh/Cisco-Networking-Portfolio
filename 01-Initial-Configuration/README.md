Lab 01 - Cisco Initial Device Configuration

Objective

Practice basic Cisco IOS commands and configure initial settings on a Cisco router using Packet Tracer.

Configuration Tasks

- Change the router hostname.
- Configure Enable Secret password.
- Configure Console password.
- Configure VTY access password.
- Enable password encryption.
- Save running configuration to startup configuration.

Commands Used

enable
configure terminal
hostname R1
enable secret [REDACTED]
service password-encryption
line console 0
password [REDACTED]
login
end
copy running-config startup-config

Verification

The following commands are used to verify the configuration:

show running-config
show startup-config

Tools

- Cisco Packet Tracer
- Cisco IOS CLI

Project Files

- Packet Tracer simulation file (.pkt)
- Configuration screenshots

Status

Basic configuration lab - In Progress.
