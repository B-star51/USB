# USB
An Educational Survey on USB-Based Cyber Threats and Mitigation Strategies


Introduction
Universal Serial Bus (USB) technology is a cornerstone of modern computing. USB devices are used for transferring files, charging mobile phones, connecting peripherals such as printers and webcams, and many other daily activities. Despite their convenience, USBs can pose significant security risks when exploited by malicious actors.

This research survey aims to raise awareness about USB-based cyber threats, examine common attack tools and techniques, and present strategies for preventing these types of attacks.


Common Types of USB Devices
USB devices are widely used and come in many forms. Common examples include:

Flash Drives – For portable data storage and file sharing.

Keyboards and Mice – Human Interface Devices (HIDs) essential for input.

Printers and Scanners – Used for handling physical documents.

Webcams and Microphones – Important for video conferencing and audio input.

Smartphone Chargers – Used for charging and syncing mobile devices.

External Hard Drives – Provide backup and large-scale data storage.

USB Hubs and Splitters – Allow multiple USB devices to connect to one port.

Wearables – Devices such as fitness trackers that often use USB for syncing.


Understanding USB Connector Types
While USB connectors may seem like a matter of hardware design, they also play a key role in security. Attackers often disguise malicious USB devices using familiar connector types to avoid suspicion.

Common USB Connectors:
USB-A – The traditional rectangular plug found on most computers.

USB-C – A newer, reversible connector commonly used in smartphones and laptops.

Micro-USB – An older standard still found in smaller electronics.

Security Note: Malicious USBs can be disguised as chargers, cables, or common adapters. Visual inspection alone is not enough to determine their safety.

Common USB-Based Attack Devices

1. USB Rubber Ducky - — *The Flash Drive That Hacks*

At first glance, a **USB Rubber Ducky** looks like an ordinary flash drive. But instead of storing files, it acts like a **keyboard**. The moment it's plugged in, it types out commands at lightning speed — opening programs, downloading malware, or stealing data.

 Why It’s Dangerous:
- **Instant Execution** – Launches attacks immediately.
- **No Antivirus Alerts** – Most security tools trust keyboards.
- **Looks Harmless** – Perfect for tricking unsuspecting users.
- **Works Everywhere** – Can attack Windows, macOS, and Linux systems.

 Real-World Example:
You find a free USB stick lying around and plug it in. In seconds, a hidden script starts running — your files are stolen, and your system is compromised. All without clicking a single thing.

2. USB Killer — *The Device That Anihilates Computers*
A **USB Killer** is a malicious gadget disguised as a regular flash drive. When you plug it in, it doesn’t hack — it *physically fries* the device.

 What It Does:
It converts the USB port’s 5V power into bursts of up to −200V, releasing it back into the system and damaging or destroying the motherboard.

 Why It’s Dangerous:
A single USB Killer can destroy a laptop, server, or phone in seconds — no software needed.

3. USB Thief — *Stealing Data Silently*

The **USB Thief** is malware loaded onto a flash drive. When connected to a computer, it silently copies files and sensitive information — without installing anything on the system, making it hard to detect.

4. Bash Bunny — *Multi-Payload USB Attacker*

The **Bash Bunny** is a powerful tool that mimics different USB devices (keyboard, Ethernet adapter, etc.). Once plugged in, it can:

- Inject keystrokes like a Rubber Ducky
- Scan the network
- Copy or modify files

It’s like a Swiss Army knife for hackers.

5. Cactus WHID — *Wi-Fi Controlled Rubber Ducky*

This is a **wireless version** of the Rubber Ducky. It connects to a Wi-Fi network, allowing attackers to trigger payloads remotely — meaning they don't even need to be in the same room.

6. Flipper Zero — *The Hacker’s Multi-Tool*

**Flipper Zero** looks like a toy but is a serious hacking gadget. It can emulate USB keyboards, read RFID/NFC cards, and even act like a universal remote. While it's popular among security researchers, it can also be misused for attacks.

7. USB Keyloggers — *Recording Every Keystroke*

These devices are placed between a keyboard and USB port. They silently record every key you type — including passwords, private messages, and credit card numbers.

8. Juice Jacking — *When Charging = Hacking*

Public USB charging stations can be risky. In a **juice jacking attack**, a malicious port or charger can install malware on your phone or extract data while it charges.

## Tip: Always use your own charging brick or a "USB data blocker" to avoid this.

9. BadUSB Attacks — *Reprogramming USB Devices for Evil*

**BadUSB** is a class of attacks where the *firmware* (the code that controls how a USB device behaves) is modified to turn a harmless-looking USB device into something malicious.

These attacks are dangerous because:

- The USB still works normally (e.g., it stores files, charges your phone).
- The malicious code is hidden in the device firmware — not the files.
- Antivirus software typically doesn’t scan or detect firmware changes.

What Can a BadUSB Do?

- Pretend to be a keyboard and type commands.
- Install malware silently.
- Redirect internet traffic to fake websites.
- Disable system defenses.
- Steal data and send it to an attacker.

10. USB Drop Attack
In a USB drop attack, attackers leave infected USB devices in public spaces, hoping that unsuspecting individuals will pick them up and connect them to their computers. Once inserted, the USB dropper installs malware or initiates a phishing attack to initiate data transfer, provide remote access, or compromise the victim’s system.

 Final Thoughts

USB devices are everywhere. But as you've seen, their usefulness can be twisted into powerful attack vectors. It's important to stay aware, be cautious with unknown devices, and always think twice before plugging something in.

Real-World USB-Based Attacks
Incident	Description
Stuxnet (2010)	Malware that targeted Iran’s nuclear program, spread through infected USB drives.
USB Drop Experiment	60% of individuals plugged in unknown USB drives found in parking lots.


Preventing USB-Based Cyber Attacks
To minimize risks from malicious USB activity, implement the following strategies:

Do Not Use Unknown USB Devices – Never plug in unverified or found USBs.

Educate Users – Raise awareness about the dangers of USB attacks.

Disable AutoRun – Prevent automatic execution of files on USB insertion.

Keep Systems Updated – Patch operating systems and software regularly.

Enable Write Protection – Prevent USB devices from modifying data.

Use USB Security Software – Tools that monitor and block unauthorized device activity.

Run Regular Antivirus Scans – Scan USB devices before opening files.

Limit USB Use – Encourage secure cloud sharing or network storage over USB reliance.

Use USB Data Blockers – Devices that allow charging without data transfer.


# Statistics 
 Accroding to an Article written by Honeywell in the year of 2024 51% of malware attcks are designed for USB attacks, a nearly six-fold increase from 9% in 2019. Making USB's a serious threat. 




| **Tool**            | **Price (Approx.)**              | **Functionality**                                                             |
| ------------------- | -------------------------------- | ----------------------------------------------------------------------------- |
| **Rubber Ducky**    | \$119.00                         | Emulates a keyboard, types malicious scripts rapidly.                         |
| **Juice Jacking**   | \$45.00 – \$420.00               | Hardware used to exploit data ports on public chargers.                       |
| **USB Killer**      | \$99.99                          | Physically destroys devices by sending high-voltage surges.                   |
| **Bash Bunny**      | \$249.99                         | Multi-function USB emulating keyboard, Ethernet, storage, etc.                |
| **Cactus WHID**     | \$24.99                          | Wi-Fi-controlled payload delivery tool (Rubber Ducky variant).                |
| **Flipper Zero**    | \$199.00                         | Multi-tool: USB attacks, RFID/NFC, remote control emulation, debugging.       |
| **USB Keyloggers**  | \$49.99 – \$139.99               | Records every keystroke between keyboard and USB port.                        |
| **BadUSB**          | \$21.99                          | Reprograms device firmware to act maliciously while appearing normal.         |
| **USB Drop Attack** | Cost of USB only (\~\$5 or less) | Social engineering attack using planted malicious USB drives in public areas. |


Final Security Reminder
“Don’t take candy from strangers — don’t take USBs from strangers!”
Just because it looks like a harmless drive doesn’t mean it’s safe. Trust your source or don’t plug it in.
