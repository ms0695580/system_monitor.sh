# System Monitor Script

## Overview

This bash script provides a comprehensive system monitoring dashboard. It displays information such as CPU and memory usage, network statistics, disk usage, system load, process monitoring, and essential service statuses.

## Features

- **Top 10 Most Used Applications:** Displays the top 10 applications consuming the most CPU and memory.
- **Network Monitoring:** Shows the number of concurrent connections, packet drops, and network traffic in and out.
- **Disk Usage:** Displays disk space usage by mounted partitions, highlighting partitions using more than 80% of the space.
- **System Load:** Shows the current load average and a breakdown of CPU usage (user, system, idle, etc.).
- **Memory Usage:** Displays total, used, and free memory, along with swap memory usage.
- **Process Monitoring:** Displays the number of active processes and shows the top 5 processes by CPU and memory usage.
- **Service Monitoring:** Monitors the status of essential services like `sshd`, `nginx/apache`, `iptables`, etc.
- **Custom Dashboard:** Users can view specific parts of the dashboard using command-line switches like `-cpu`, `-memory`, `-network`, etc.

## Usage

### Running the Script

Make the script executable (if you haven't already):

```bash
chmod +x system_monitor.sh
