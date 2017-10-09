# About
`pushjet-cli` is a simple shell/CLI interface to the PushJet API with minimum requiremens.

# Requirements
**bash**
**curl**

# Configuration
Default configuration file locations:

    ~/.config/pushjet-cli
    /etc/pushjet-cli

Configuration options:

    SECRET=     # Default service secret key
    SERVERURL=  # Custom server URL

# Usage
    -m "<message>"   - The notification text.
    -t "<title>"     - A custom message title. [optional] 
    -l <level>       - The importance level from 1(low) to 5(high). [default 3]
    -u <link>        - An optional link. 
    -s <secret>      - The service secret token.
    -S               - Custom server URL.
    -C               - Custom configuration.    
    -h               - Show help.
