# Python Port Scanner

## Project Description

The Python Port Scanner is a simple networking project that checks whether selected ports on a target website or IP address are open or closed.

## Technologies Used

* Python
* Socket Module
* TCP Networking

## Features

* Accepts a website or IP address as input.
* Scans seven predefined ports.
* Displays whether each port is open or closed.
* Uses a timeout to avoid waiting too long for a connection.

## Ports Scanned

* 21 – FTP
* 22 – SSH
* 23 – Telnet
* 25 – SMTP
* 53 – DNS
* 80 – HTTP
* 443 – HTTPS

## Requirements

* Python 3
* Basic knowledge of networking

## How to Run

1. Clone or download this repository.

2. Open the project folder in a terminal.

3. Run the following command:

   `python scanner.py`

4. Enter the target hostname or IP address when prompted.

5. View the port scanning results in the terminal.

## Sample Output

```text
Enter website or IP: example.com

Scanning target: example.com

Port 21 is CLOSED
Port 22 is OPEN
Port 23 is CLOSED
```

*Sample output only. Actual results depend on the target and network.*

## Learning Outcomes

* Understanding Python socket programming.
* Learning the basics of TCP connections.
* Understanding open and closed ports.
* Practicing basic network security concepts.

## Disclaimer

This tool is intended for educational purposes. Scan only systems you own or have explicit permission to test.
