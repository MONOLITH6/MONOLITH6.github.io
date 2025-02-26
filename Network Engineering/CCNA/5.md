## Theory in short
### Understanding Cisco CLI and Network Device Configuration

A Cisco device can be configured using a **Command-Line Interface (CLI)** or a **Graphical User Interface (GUI)**. While GUIs are user-friendly, CLIs are preferred for network configuration due to their efficiency and detailed control.

To access the CLI of a Cisco device, you can connect:
- **Via Console Port** using a cable directly from a PC.
- **Remotely** via Telnet or Secure Shell (SSH) over the network.

When working in the CLI, different **modes** are available:
1. **User EXEC Mode (Router>)** – Limited commands, mostly for viewing information.
2. **Privileged EXEC Mode (Router#)** – Provides access to advanced commands.
3. **Global Configuration Mode (Router(config)#)** – Used to make configuration changes.
4. **Other Configuration Modes (e.g., Interface, Line, etc.)** – Used for specific settings.

Cisco IOS devices use two configuration files:
- **Running-config** (in RAM): Stores the current configuration, lost after reboot.
- **Startup-config** (in NVRAM): Stored settings that persist after reboot.

Security measures include setting **enable passwords** and **enable secrets** to restrict unauthorized access. Enable passwords can be stored in plaintext or encrypted, while enable secrets are hashed for better security.

---

## Questions

### Multiple-choice questions

1.1. What is the purpose of the CLI on a Cisco device?
A) To provide a graphical interface for network configuration  
B) To allow text-based command input for configuration  
C) To browse the internet  
D) To install software applications  

1.2. Which mode provides access to all available EXEC commands?
A) User EXEC mode  
B) Privileged EXEC mode  
C) Global Configuration mode  
D) Interface Configuration mode  

1.3. What is required to connect a PC to a Cisco device via the console port?
A) Ethernet cable  
B) Rollover cable  
C) HDMI cable  
D) Coaxial cable  

1.4. Which command is used to enter Global Configuration mode?
A) enable  
B) configure terminal  
C) exit  
D) reload  

1.5. What is the function of the startup-config file?
A) Stores the current configuration in RAM  
B) Stores the persistent configuration in NVRAM  
C) Runs diagnostics on Cisco devices  
D) Provides a user interface  

1.6. Which of the following commands saves the running configuration to startup-config?
A) copy startup-config running-config  
B) write erase  
C) copy running-config startup-config  
D) reload  

1.7. What does the command `reload` do?
A) Saves the configuration  
B) Exits privileged mode  
C) Restarts the device  
D) Displays the routing table  

1.8. How can you encrypt an enable password stored in the configuration?
A) enable secret  
B) service password-encryption  
C) hash password  
D) encrypt password  

1.9. Which CLI command is used to move from User EXEC mode to Privileged EXEC mode?
A) enable  
B) configure terminal  
C) disable  
D) logout  

1.10. What is the benefit of using `enable secret` instead of `enable password`?
A) It is easier to remember  
B) It uses stronger encryption  
C) It does not require authentication  
D) It prevents unauthorized shutdowns  

---

### Short Answer Questions

2.1. What are two ways to access the CLI of a Cisco device?  
2.2. What is the difference between User EXEC mode and Privileged EXEC mode?  
2.3. Why is the enable secret more secure than the enable password?  
2.4. What command is used to erase the startup-config file?  
2.5. Explain the function of the `do` command when used in a configuration mode.  

---

### Match Terms

3.1. Set 1
A) Running-config  
B) Startup-config  
C) Privileged EXEC mode  

1) Configuration that is active and lost on reboot  
2) Configuration stored in NVRAM and persists after reboot  
3) Mode allowing full access to device commands  

3.2. Set 2
A) User EXEC mode  
B) Global Configuration mode  
C) Terminal Emulator  
D) Console Cable  

1) Software used to access a Cisco device's CLI  
2) Provides basic view-only commands  
3) Used to configure a network device  
4) Required for direct connection to a Cisco device  

3.3. Set 3
A) Rollover Cable  
B) Telnet  
C) Secure Shell (SSH)  
D) Enable Secret  
E) Write command  

1) A cable for direct access to the console port  
2) Remote access method that is NOT encrypted  
3) Encrypted remote access protocol  
4) More secure alternative to enable password  
5) Saves running-config to startup-config  

---

### Select All That Apply

4.1. Which of the following are Cisco CLI configuration modes?
A) User EXEC mode  
B) Global Configuration mode  
C) Web Configuration mode  
D) Privileged EXEC mode  

4.2. Which of the following methods can be used to access a Cisco device’s CLI?
A) Console port  
B) Telnet  
C) SSH  
D) HDMI  

---

### Oral Question

5.1. Explain in simple terms how a Cisco device saves its configuration and why it’s important.

---

## Answer Key

1.1 B  
1.2 B  
1.3 B  
1.4 B  
1.5 B  
1.6 C  
1.7 C  
1.8 B  
1.9 A  
1.10 B  

2.1 Console port, SSH/Telnet  
2.2 User EXEC is limited, Privileged EXEC allows configuration  
2.3 Enable secret is hashed, making it more secure  
2.4 write erase  
2.5 Allows execution of EXEC mode commands from configuration mode  

3.1 A1, B2, C3  
3.2 A2, B3, C1, D4  
3.3 A1, B2, C3, D4, E5  

4.1 A, B, D  
4.2 A, B, C  

5.1 A Cisco device saves its configuration in two files: running-config (active but lost on reboot) and startup-config (saved permanently). This ensures that the device retains its settings after a restart, similar to how a smartphone keeps its settings even when turned off.  

---

## Empty Sheet

1.
1.  
2.  
3.  
4.  
5.  
6.  
7.  
8.  
9.  
10.  

2.1  
2.2  
2.3  
2.4  
2.5  

3.1  
A  
B  
C  

3.2  
A  
B  
C  
D  

3.3  
A  
B  
C  
D  
E  

4.1  
4.2  

5.  

---

