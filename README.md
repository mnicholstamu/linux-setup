# Personal Linux Setup
This is my first deep dive into setting up my Linux development environment. 

## Computer / OS
- Hardware
  - Dell Inspiron 14” Laptop (model: i7440-7304BLU-PUS)
    - Intel Core 7 Series 1
    - 1tb SSD
    - 16gb RAM
- OS
  - Pop_OS [download](https://pop.system76.com/)

## Software
  - Browser(s)
      - [Firefox](https://www.mozilla.org/en-US/firefox/all/#product-desktop-release)
      - [Google Chrome](https://www.google.com/chrome/)
  - Screen Capture
    - [OBS Studio](https://obsproject.com/)
  - Meetings/Communications
    - [Slack](https://slack.com/downloads/linux)
    - [Zoom](https://zoom.us/download?os=linux)
  - Office Suite
    - LibreOffice
  - IDE(s)
    - [VS Code](https://code.visualstudio.com/)
    - [WebStorm](https://www.jetbrains.com/webstorm/)
  - WP Development (for work)
    - [Local](https://localwp.com/help-docs/getting-started/installing-local/)
## Fingerprint scan for login
`sudo apt install fprintd libpam-fprintd`
 `sudo pam-auth-update`


Restart the computer and then go into Settings > Users > [User]. Click on Fingerprint Login to enable it.
![image](https://github.com/mnicholstamu/linux-setup/assets/128824999/5c9eed79-2f0a-433d-b4ec-59ea9463ae8d)
![image](https://github.com/mnicholstamu/linux-setup/assets/128824999/6d504bfd-6cfc-43f6-bdf8-29331580cc6f)



## Node / NVM
```sudo apt install nodejs
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash
source ~/.nvm/nvm.sh
nvm install --lts
nvm use [version]
