# Wi-Fi Connected But No Internet

## Scenario

Laptop connected to Wi-Fi network but internet access was unavailable.

---

## Symptoms Observed

* Wi-Fi connected successfully
* Websites not loading
* Applications unable to access internet

---

## Troubleshooting Steps

### 1. Checked Network Status

Verified Wi-Fi connection status from Windows network settings.

### 2. Used Command-Line Tools

Ran basic network diagnostic commands.

```bash
ipconfig
ping 8.8.8.8
ping google.com
```

### 3. Diagnosed DNS Issue

Ping to IP address worked, but domain name failed to resolve.

### 4. Restarted Router and Reconnected

Restarted router and reconnected laptop to Wi-Fi network.

### 5. Flushed DNS Cache

Executed:

```bash
ipconfig /flushdns
```

---

## Tools Used

* Command Prompt
* Windows Network Settings
* Router restart
* DNS troubleshooting

---

## Outcome

Internet connectivity restored successfully after DNS troubleshooting and router restart.

---

## Skills Practiced

* Basic networking
* DNS troubleshooting
* Command-line diagnostics
* Wi-Fi troubleshooting
