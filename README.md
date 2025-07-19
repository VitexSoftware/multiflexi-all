# multiflexi with all addons

![GitHub issues](https://img.shields.io/github/issues/VitexSoftware/multiflexi-all.svg)

Debian metapackage to install all availble MultiFlexi addons

## Installation
```bash
sudo apt install lsb-release wget apt-transport-https bzip2

wget -qO- https://repo.vitexsoftware.com/keyring.gpg | sudo tee /etc/apt/trusted.gpg.d/vitexsoftware.gpg
echo "deb [signed-by=/etc/apt/trusted.gpg.d/vitexsoftware.gpg]  https://repo.vitexsoftware.com  $(lsb_release -sc) main" | sudo tee /etc/apt/sources.list.d/vitexsoftware.list
sudo apt update

sudo apt install multiflexi-all
```

![img](install.jpg?raw=true)

MultiFlexi
----------

All included applications are ready to run in the [MultiFlexi](https://multiflexi.eu) environment.
See the full list of ready-to-run applications within the MultiFlexi platform on the [application list page](https://www.multiflexi.eu/apps.php).

[![MultiFlexi App](https://github.com/VitexSoftware/MultiFlexi/blob/main/doc/multiflexi-app.svg)](https://www.multiflexi.eu/apps.php)









## Packages included

| Name | URL |
|------|-----|
| multiflexi |  |
| multiflexi-abraflexi |  |
| multiflexi-abraflexi-cashier |  |
| multiflexi-abraflexi-client-check |  |
| multiflexi-abraflexi-contract-invoices |  |
| multiflexi-abraflexi-digest |  |
| multiflexi-abraflexi-email-importer |  |
| multiflexi-abraflexi-ipex |  |
| multiflexi-abraflexi-kimai-importer |  |
| multiflexi-abraflexi-mailer |  |
| multiflexi-abraflexi-matcher |  |
| multiflexi-abraflexi-pricefixer |  |
| multiflexi-abraflexi-raiffeisenbank |  |
| multiflexi-abraflexi-reminder |  |
| multiflexi-abraflexi-revolut |  |
| multiflexi-abraflexi-tools |  |
| multiflexi-api |  |
| multiflexi-csas-authorize |  |
| multiflexi-csas-statement-tools |  |
| multiflexi-discomp2abraflexi |  |
| multiflexi-docker |  |
| multiflexi-fiobank-statement-tools |  |
| multiflexi-mtr |  |
| multiflexi-pohoda-client-checker |  |
| multiflexi-pohoda-raiffeisenbank |  |
| multiflexi-pohoda-realpad |  |
| multiflexi-raiffeisenbank |  |
| multiflexi-raiffeisenbank-statement-tools |  |
| multiflexi-realpad2mailkit |  |
| multiflexi-redmine2abraflexi |  |
| multiflexi-sms-input |  |
| multiflexi-subreg2abraflexi |  |
| multiflexi-zabbix |  |

Please refer to the individual package documentation for more information.
