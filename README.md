# Devloper-Smtp-Server

## Overview
Devloper-Smtp-Server is a tiny SMTP server that is designed to allow developers to quickly check the mail sending functions of their application are working.

### Features
- Simple GUI
- Multi-threaded, allows you to plug the server component into your own solution


## Use
1. Start the server with:
        DeveloperSmtpGui.exe
2. Point your mail-sending application to localhost, on port 25.
3. Send your mail, get satisfaction from the fact that it shows in server's window.

That's it.


## Slightly more complicated use
You can customise the port and ip address being used by the server. All configurations are contained in the App.config file.

#### Ip Address Binding
The line below defines the Ip Address being used by Super-Smtp-Sever.
    <add key="SuperSmtpIp" value="any"/>

- *Any* means any ip address that your computer has.
- If you want to specify an ip address, put it in standard IP for. (eg. 192.168.1.10)

#### Port Binding
The line below defines the port that Super-Smtp-Server uses.
    <add key="SuperSmtpPort" value="25"/>
