Name: HARSHINI P

Company:CODTECH IT SOLUTIONS

ID:CT08DS4093

Domain:CYBERSECURITY & ETHICALHACKING

Duration:July to August 2024

Mentor:NEELA SANTHOSH KUMAR

OVERVIEW OF THIS PROJECT:

Project:Vulnerability Scanning Tool

Objective
The provided Java code demonstrates a basic network port scanner. This tool scans a given IP address to identify open ports within a specified range.

Key Activities:

1. Imports:
   - java.io.IOException: Used to handle input/output exceptions.
   - java.net.InetSocketAddress: Encapsulates a socket address with a hostname and a port number.
   - java.net.Socket: Provides a client socket to connect to the specified IP address and port.

2. Main Method:
   - Arguments Handling:
     - args[0]: The IP address to scan.
     - args[1] (optional): The starting port number for the scan (default is 1 if not provided).
     - args[2] (optional): The ending port number for the scan (default is 65535 if not provided).
   - Usage Validation: Checks if the IP address is provided and prints usage instructions if not.
   - Calling scanPorts: Initiates the port scanning process with the provided arguments.

3. scanPorts Method:
   - Input Parameters:
     - ipAddress: The target IP address for scanning.
     - startPort: The starting port number.
     - endPort: The ending port number.
   - Port Scanning Loop:
     - Iterates over the port range from startPort to endPort.
     - Attempts to establish a socket connection to each port.
     - If the connection is successful within the specified timeout (100 milliseconds), it prints that the port is open.
     - If the connection fails (throws an IOException), it means the port is closed or not reachable.
   - Completion Message: Prints a message indicating the scan is complete.

   OUTPUT:
   ![image](https://github.com/user-attachments/assets/590cbb11-bd74-4cdf-b69e-3c98aa5a61cf)

