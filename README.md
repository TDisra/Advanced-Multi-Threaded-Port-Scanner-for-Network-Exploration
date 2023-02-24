# Advanced Multi Threaded Port Scanner for Network Exploration
Advanced network port scanner that can scan networks for open ports. The scanner uses threading to improve its efficiency and speed. It can scan a range of ports on a given IP address and report the open ports, along with the service running on each open port. The scanner also keeps track of IP addresses that are not reachable during the scan.

### Features
Scans a range of IP addresses for open ports
Uses multi-threading for faster scanning
Displays the service running on each open port
Can be customized to scan specific port ranges and use a different number of threads

### Installation
To use this port scanner, you'll need to have Python 3 installed on your machine. You can download Python 3 from the official Python website.

Once you have Python 3 installed, simply clone this repository to your local machine:
git clone https://github.com/your-username/advanced-port-scanner.git

### Usage
To run the port scanner, simply navigate to the directory where the script is located and run the following command:
python port_scanner.py <ip_address> <first_port> <last_port> <num_threads>
