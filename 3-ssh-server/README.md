# SSH Server Configuration

---

## Screenshots

### SSH Server Installation

OpenSSH Server was successfully installed on Ubuntu, enabling secure remote administration capabilities.

![SSH Server Installation](screenshots/01-lnx-ssh-installed.png)

---

### SSH Service Status

Verified that the SSH service was running correctly and accepting connections on the default SSH port (22).

![SSH Service Status](screenshots/02-lnx-ssh-listening-port-22.png)

---

### SSH Configuration Update

The SSH server configuration file (`sshd_config`) was updated to change the default SSH listening port.

![SSH Configuration Update](screenshots/03-lnx-ssh-config-file-updated.png)

---

### Custom SSH Port Verification

Confirmed that the SSH service was successfully listening on the new custom port (2222), proving the configuration changes were applied successfully.

![Custom SSH Port Verification](screenshots/04-lnx-ssh-listening-port-changed-to-2222.png)

---

### Remote SSH Access from Windows

Successfully established a secure SSH connection from a Windows client to the Ubuntu server using the custom SSH port (2222), confirming successful remote administration.

![Remote SSH Access from Windows](screenshots/05-lnx-ssh-server-remote-access-on-windows.png)