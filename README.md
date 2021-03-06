[![Travis (.com)](https://img.shields.io/travis/com/dewgew/Domoticz-Google-Assistant?logo=travis)](https://travis-ci.com/DewGew/Domoticz-Google-Assistant) [![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/dewgew/domoticz-google-assistant?logo=docker)](https://hub.docker.com/r/dewgew/domoticz-google-assistant) ![GitHub release (latest by date)](https://img.shields.io/github/v/release/dewgew/Domoticz-Google-Assistant?logo=github) [![Discord](https://img.shields.io/discord/664815298284748830?logo=discord)](https://discordapp.com/invite/AmJV6AC)
# Domoticz-Google-Assistant 

<img src="dzga_UI.png" alt="drawing" width="600"/>

Standalone implementation for [Domoticz Home Automation](https://www.domoticz.com/). It means that you can put this server wherever you want, even on another machine. You need to setup a project in Actions on Google Console. You find instructions below.

Based on Pawcio's script at [Domoticz Forum](https://www.domoticz.com/forum/viewtopic.php?f=69&t=27244)

Required:
- public url
- python >= 3.5
- Make local deployment available trough HTTPS with valid certificate with one below:
  - SSL with own domain or dynamic DNS, require ssl key and ssl certficate
  - Use ngrok for a secure SSL tunnel with valid public HTTPS URL
  - Configure reverse proxy with valid certificate using Lets Encrypt

Domoticz-Google-Assistant delivers: 
- The oauth authorization and smarthome endpoint for the google assistant.
- Two-factor authentication pin for domoticz protected devices. (limited language support)
- Acknowledgement with Yes or No. (limited language support)
- Arm Disarm Securitypanel. (limited language support)
- On/Off, Brightness, Thermostat, Color Settings, speaker volume, Lock/Unlock, Scene and Open/Close.
- Stream surveillance camera to chromecast.
- Toggle Selector switches.
- Ngrok, instantly create a public HTTPS URL. Don't have to open any port on router and do not require a reverse proxy.
- **NEW** Modes for thermostat

Please feel free to modify it, extend and improve

# Installation
Just open a terminal window and execute this command. Then set up [Actions on Google](https://github.com/DewGew/Domoticz-Google-Assistant/wiki). Thats it!
```bash
bash <(curl -s https://raw.githubusercontent.com/DewGew/dzga-installer/master/install.sh)
```

### [Installation and configuration wiki](https://github.com/DewGew/Domoticz-Google-Assistant/wiki)
### [Docker install](https://github.com/DewGew/Domoticz-Google-Assistant/wiki/DZGA-with-Docker)
<!--stackedit_data:
eyJoaXN0b3J5IjpbNjY2NTI2ODUyXX0=
-->
