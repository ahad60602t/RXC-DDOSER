RXC DDOSER

Simple ddos tool

Installation

    Clone the repository:

    bash

git clone https://github.com/ahad60602t/

Navigate into the project directory:

bash

cd RXC-DDOSER

Install dependencies:
   bash
   pip3 install -r requirments.txt

Usage

    Modify headers.txt with your desired HTTP headers.
    Run the script with Python 3:

    php

    python3 rxc_ddoser.py -s <server_ip> -p <port> -t <turbo>

    Replace <server_ip>, <port>, and <turbo> with your server IP, port, and turbo value respectively.

Options

    -s <server_ip>: Specify the server IP to attack.
    -p <port>: Specify the port (default is 80).
    -t <turbo>: Specify the turbo value (default is 135).

Example

css

python3 rxc_ddoser.py -s 192.168.1.1 -p 80 -t 200

Disclaimer

This tool is intended for server stress testing purposes only. Use responsibly and legally. Your IP address is visible during usage.
License

Author

NASIF HIMADRI

    GitHub: https://github.com/ahad60602t

Feedback

If you have any feedback, please create an issue or reach out to [nasifhimadri@gmail.com].
