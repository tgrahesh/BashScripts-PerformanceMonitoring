# Bash Performance Monitoring and Alerting Tool

This Bash script is designed to monitor system resources (CPU, Memory, Disk I/O, Network) and send alerts when thresholds are crossed. 

## System Deployment

### Prerequisites

1. A Linux server (e.g., AWS EC2) with a LAMP (Linux, Apache, MySQL, PHP) stack.
2. Ensure that the server is secured using firewalls and follows security best practices.

### Deployment Steps

1. **Set Up a LAMP Stack on Your Server:**
   - Install Linux, Apache, MySQL, and PHP on your server. You can use package managers like `apt` for Ubuntu or `yum` for CentOS.

2. **Deploy the Bash Script on LAMP Stack:**
   - Copy the Bash script to your server. You can use `scp` or any other method.
   - Make sure the script is executable by running `chmod +x yourfilename.sh`.

3. **Configure Alerting Thresholds:**
   - Edit the script to set your desired thresholds for CPU, Memory, Disk I/O, and Network monitoring.

4. **Run the Script:**
   - Execute the script on your server, and it will continuously monitor system resources.

5. **Static IP Configuration and Reversion to DHCP:**
   - Configure a static IP on your Linux server and observe its behavior.
   - Analyze how the system responds when the static IP is reverted to DHCP.

## Usage

To use the script, simply run it on your server. You can use a command like:

```bash
./monitor.sh
