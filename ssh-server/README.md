SSH Server Configuration

## Overview

This project demonstrates the installation, configuration and management of an OpenSSH Server on Ubuntu Linux. The server was configured to accept secure remote connections, the default SSH port was changed from 22 to 2222 and remote administration from a Windows client was successfully verified.

---

## Screenshots

### SSH Server Installation

OpenSSH Server was successfully installed on Ubuntu, enabling secure remote administration capabilities.

![SSH Server Installation](screenshots/01-linux-ssh-server-installation.png)

---

### SSH Service Status

Verified that the SSH service was running correctly and accepting connections on the default SSH port (22).

![SSH Service Status](screenshots/02-linux-ssh-server-service-status.png)

---

### SSH Configuration

The SSH server configuration file (`sshd_config`) was updated to customize the server configuration and change the listening port.

![SSH Configuration](screenshots/03-linux-ssh-server-configuration.png)

---

### SSH Port Verification

Confirmed that the SSH service was successfully listening on the new custom port (2222), proving that the configuration changes were applied correctly.

![SSH Port Verification](screenshots/04-linux-ssh-server-port-2222-verification.png)

---

### Remote Login from Windows

Successfully established a secure SSH connection from a Windows client to the Ubuntu server using the custom SSH port (2222), confirming end-to-end remote administration.

![Remote Login from Windows](screenshots/05-linux-ssh-server-remote-login-from-windows.png)

