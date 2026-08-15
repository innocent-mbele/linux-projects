
# Samba File Server

## Overview

Configured an Ubuntu Linux server as a Samba file server with an authenticated SMB shared folder and verified file access from a Windows client.

## Screenshots

### 1. Samba Service Status

Shows the Samba SMB service running successfully on the Ubuntu server.

![Samba Service Status](screenshots/01-lnx-samba-service-status.png)

---

### 2. Shared Directory

Shows the directory created for the Samba shared folder.

![Shared Directory](screenshots/02-lnx-samba-shared-directory.png)

---

### 3. Samba Share Configuration

Shows the configured Samba `Shared` network share and its access settings.

![Samba Share Configuration](screenshots/03-lnx-samba-share-config.png)

---

### 4. Configuration Test

Shows the Samba configuration validated successfully using `testparm`.

![Samba Configuration Test](screenshots/04-lnx-samba-config-test.png)

---

### 5. Share List and Connection

Shows the `Shared` SMB share discovered and accessed using `smbclient`.

![Share List and Connection](screenshots/05-lnx-samba-share-list-and-connection.png)

---

### 6. File Transfer

Shows successful file transfer through the Samba share.

![File Transfer](screenshots/06-lnx-samba-file-transfer.png)

---

### 7. Windows Share Verification

Shows the Samba shared folder successfully accessed from the Windows client.

![Windows Share Verification](screenshots/07-lnx-samba-windows-share-verification.png)
