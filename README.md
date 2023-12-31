# multiflexi with all addons

[![Packaging status](https://repology.org/badge/vertical-allrepos/multiflexi-all.svg)](https://repology.org/project/multiflexi-all/versions)
[![GitHub issues](https://img.shields.io/github/issues/VitexSoftware/multiflexi-all.svg)](Debian metapackage to install all availble MultiFlexi addons)

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
| [multiflexi-abraflexi-contract-invoices](https://github.com/VitexSoftware/abraflexi-contract-invoices)| AbraFlexi contract invoices
| [multiflexi-abraflexi-digest](https://github.com/VitexSoftware/AbraFlexi-Digest)                      | AbraFlexi digest
| [multiflexi-abraflexi-email-importer](https://github.com/VitexSoftware/AbraFlexi-email-importer)      | AbraFlexi email importer
| [multiflexi-abraflexi-mailer](https://github.com/VitexSoftware/abraflexi-mailer)                      | AbraFlexi mailer
| multiflexi-abraflexi-matcher                                                                          | AbraFlexi matcher
| multiflexi-abraflexi-raiffeisenbank                                                                   | AbraFlexi Raiffeisenbank
| [multiflexi-abraflexi-reminder](https://github.com/VitexSoftware/abraflexi-reminder)                  | AbraFlexi reminder
| multiflexi-abraflexi-tools              | AbraFlexi tools
| multiflexi-api                          | MultiFlexi API
| multiflexi-discomp2abraflexi            | Discomp2AbraFlexi
| multiflexi-pohoda-client-config         | Pohoda client configuration
| multiflexi-realpad2mailkit              | RealPad2MailKit
| multiflexi-redmine2abraflexi            | Redmine2AbraFlexi
| multiflexi-subreg2abraflexi             | Subreg2AbraFlexi
| multiflexi-zabbix                       | Zabbix

![MultiFlexi](https://github.com/VitexSoftware/MultiFlexi/blob/main/multiflexi.svg?raw=true)
![Email Importer](https://github.com/VitexSoftware/AbraFlexi-email-importer/raw/main/abraflexi-imap-import.svg?raw=true)
![Mailer Logo](https://github.com/VitexSoftware/abraflexi-mailer/raw/main/project-logo.svg?raw=true)
![Reminder](https://github.com/VitexSoftware/abraflexi-reminder/raw/main/abraflexi-reminder.svg?raw=true)
![Digestor](https://github.com/VitexSoftware/AbraFlexi-Digest)
![Contractor](https://github.com/VitexSoftware/abraflexi-contract-invoices/raw/master/abraflexi-contract-invoices.svg?raw=true)
