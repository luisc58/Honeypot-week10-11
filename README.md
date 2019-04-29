# Honeypot

Honeypots deployed:
- Dionaea [ref](https://dionaea.readthedocs.io/en/latest/introduction.html)
- centos/rasberrypi - Kippo (renamed to cowrie) [ref](https://github.com/threatstream/mhn/wiki/Cowrie-Sensor)
- Kippo as vulnerable Juniper Netscreen (renamed to cowrie) [ref](https://github.com/threatstream/mhn/wiki/Cowrie-Sensor)
- shockpot [ref](https://github.com/threatstream/mhn/wiki/Shockpot-Sensor)
- wordpot [ref](https://github.com/threatstream/mhn/wiki/Wordpot-Sensor)

Issues encountered:
- Admin panel didn't include nmap package, found installation elsewhere.

- Milestone 4: instruction to click on Deploy from MHN admin console was a little unclear that you needed to use the admin IP address to login.

- GCP Project selection was unclear on what to use, create a new one or existing one?

Data Collected:
- 374 Attacks recieved
- Honey pots #4,5 didn't receive any attacks
- Honeypot Dionaea was the one with most attacks recieved (most likely from being initialized first)

Unresolved questions raised by the data collected:
- What kind of attack was being carried out? More info?
- Do the attacks directly affect the VM's?
- What use is the info that I collected for?

