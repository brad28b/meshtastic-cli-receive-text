# meshtastic-cli-receive-text
A python command line script to receive messages from Meshtastic. Run the read_messages.py script, and it will connect to your radio and display any text messages received by your node, on any channel.

# Installation
git clone https://github.com/brad28b/meshtastic-cli-receive-text.git
cd meshtastic-cli-receive-text
pip install requirements.txt

# Usage
Firstly, edit read_messages.py and set the serial port for your device (usually /dev/ttyUSB0 or /dev/ttyACM0)

Then to run the script:

python read_messages.py

To exit, use Ctrl-C
