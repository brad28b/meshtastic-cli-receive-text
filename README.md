# meshtastic-cli-receive-text
A python command line script to receive messages from Meshtastic. Run either the <b>'read_messages_serial.py'</b> script OR the <b>'read_messages_tcp.py'</b> script, and it will connect to your radio (via either Serial or TCP) and display any text messages received by your node, on any channel, including private/direct messages.

I built this because this functionality is not available using the Meshtastic CLI (as of time of publishing).

# Installation
* git clone https://github.com/brad28b/meshtastic-cli-receive-text.git
* cd meshtastic-cli-receive-text
* pip3 install -r requirements.txt

# Usage
* Firstly, decide if you will be connecting to your node via serial or via TCP. If using serial, edit read_messages_serial.py and set the serial port for your Meshtastic node (usually /dev/ttyUSB0 or /dev/ttyACM0). If using TCP, edit read_messages_tcp.py and set the IP address of your Meshtastic node.
* Then to run the script:
* For Serial: python read_messages_serial.py
* For TCP: python read_messages_tcp.py

* To exit, use Ctrl-C

![Screenshot 2024-07-09 121441](https://github.com/brad28b/meshtastic-cli-receive-text/assets/70585927/1217ff9f-0b42-4c30-818f-5d96e3d2522e)

![Screenshot 2024-07-09 121720](https://github.com/brad28b/meshtastic-cli-receive-text/assets/70585927/2b63295b-095d-42eb-8f9b-e48844c51055)
