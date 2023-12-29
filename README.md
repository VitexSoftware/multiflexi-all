# multiflexi-all
Debian metapackage to install all availble MultiFlexi addons

## Installation
```bash
sudo apt install lsb-release wget apt-transport-https bzip2

wget -qO- https://repo.vitexsoftware.com/keyring.gpg | sudo tee /etc/apt/trusted.gpg.d/vitexsoftware.gpg
echo "deb [signed-by=/etc/apt/trusted.gpg.d/vitexsoftware.gpg]  https://repo.vitexsoftware.com  $(lsb_release -sc) main" | sudo tee /etc/apt/sources.list.d/vitexsoftware.list
sudo apt update

sudo apt install multiflexi-all
```

## Packages included

| Package                                                                                               | Description             |
|-------------------------------------------------------------------------------------------------------|-------------------------|
| [multiflexi](https://github.com/VitexSoftware/MultiFlexi)                                             | MultiFlexi main package |
| multiflexi-abraflexi-client-config                                                                    | AbraFlexi client configuration
| multiflexi-abraflexi-contract-invoices                                                                | AbraFlexi contract invoices
| multiflexi-abraflexi-digest                                                                           | AbraFlexi digest
| [multiflexi-abraflexi-email-importer](https://github.com/VitexSoftware/AbraFlexi-email-importer)      | AbraFlexi email importer
| [multiflexi-abraflexi-mailer](https://github.com/VitexSoftware/abraflexi-mailer)                      | AbraFlexi mailer
| multiflexi-abraflexi-matcher                                                                          | AbraFlexi matcher
| multiflexi-abraflexi-raiffeisenbank                                                                   | AbraFlexi Raiffeisenbank 
| multiflexi-abraflexi-reminder           | AbraFlexi reminder
| multiflexi-abraflexi-tools              | AbraFlexi tools
| multiflexi-api                          | MultiFlexi API
| multiflexi-discomp2abraflexi            | Discomp2AbraFlexi
| multiflexi-pohoda-client-config         | Pohoda client configuration
| multiflexi-realpad2mailkit              | RealPad2MailKit
| multiflexi-redmine2abraflexi            | Redmine2AbraFlexi
| multiflexi-subreg2abraflexi             | Subreg2AbraFlexi
| multiflexi-zabbix                       | Zabbix

![MultiFlexi](https://github.com/VitexSoftware/MultiFlexi/blob/main/multiflexi.svg?raw=true |width=100)
![Email Importer](https://github.com/VitexSoftware/AbraFlexi-email-importer/raw/main/abraflexi-imap-import.svg?raw=true |width=100)
![Mailer Logo](https://github.com/VitexSoftware/abraflexi-mailer/raw/main/project-logo.svg?raw=true | width=100)
