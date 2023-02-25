Sendfile Attack Script
This is a C script that performs a Sendfile attack. It creates a file called "sendfile1" of size 64 MB and uses the sendfile() function to send it over a socket to a listening server on port 31337. While the file is being sent, it opens the file "kmem" and writes all received data to it.

Installation
To run this script, you must have a C compiler installed on your system. You can compile the script using the following command:

gcc -o sendfile sendfile.c

Usage
To use the script, first run the compiled executable:

./sendfile

The script will create the file "sendfile1" and start sending it over the socket to the listening server on port 31337. While the file is being sent, it will write all received data to the file "kmem".

Disclaimer
This script is for educational purposes only. The author takes no responsibility for any illegal use of this script.
