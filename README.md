# Port-scanner
This python script scans a range of ports on a target host, reporting open ports with concurrency control.

This Python script performs asynchronous port scanning using the asyncio library to check a range of ports on a specified target host. It limits the number of concurrent port scan tasks with a semaphore to avoid overwhelming the system. The script attempts to establish a connection to each port and reports any open ports. If a connection fails or times out, it moves on to the next port. The scan time is recorded and displayed, and any errors, such as invalid input or hostname resolution issues, are handled accordingly. Open ports are listed at the end of the scan.

