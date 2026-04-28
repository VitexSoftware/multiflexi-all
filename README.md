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
| csas-sharepoint | https://github.com/VitexSoftware/csas-sharepoint |
| multiflexi | https://github.com/VitexSoftware/MultiFlexi |
| multiflexi-abraflexi | https://github.com/VitexSoftware/multiflexi-abraflexi |
| multiflexi-abraflexi-cashier | https://github.com/VitexSoftware/abraflexi-cashier |
| multiflexi-abraflexi-client-check | https://github.com/VitexSoftware/php-abraflexi-config |
| multiflexi-abraflexi-contract-invoices | https://github.com/VitexSoftware/abraflexi-contract-invoices |
| multiflexi-abraflexi-digest | https://github.com/VitexSoftware/AbraFlexi-Digest |
| multiflexi-abraflexi-email-importer | https://github.com/VitexSoftware/AbraFlexi-email-importer |
| multiflexi-abraflexi-ipex | https://github.com/Spoje-NET/abraflexi-ipex |
| multiflexi-abraflexi-kimai-importer | https://github.com/VitexSoftware/Kimai2AbraFlexi/settings |
| multiflexi-abraflexi-mailer | https://github.com/VitexSoftware/php-abraflexi-mailer |
| multiflexi-abraflexi-matcher | https://github.com/VitexSoftware/php-abraflexi-matcher |
| multiflexi-abraflexi-pricefixer | https://github.com/VitexSoftware/AbraFlexi-pricefixer |
| multiflexi-abraflexi-raiffeisenbank | https://github.com/VitexSoftware/abraflexi-raiffeisenbank |
| multiflexi-abraflexi-reminder | https://github.com/VitexSoftware/abraflexi-reminder |
| multiflexi-abraflexi-revolut | https://github.com/VitexSoftware/AbraFlexi-Revolut |
| multiflexi-abraflexi-tools | https://github.com/VitexSoftware/AbraFlexi-Tools |
| multiflexi-abraflexi-ui | https://github.com/VitexSoftware/multiflexi-abraflexi |
| multiflexi-api | https://github.com/VitexSoftware/MultiFlexi |
| multiflexi-cli | https://github.com/VitexSoftware/multiflexi-cli |
| multiflexi-common | https://github.com/VitexSoftware/MultiFlexi |
| multiflexi-csas-authorize | https://github.com/Spoje-NET/csas-authorize |
| multiflexi-csas-sharepoint | https://github.com/VitexSoftware/csas-sharepoint |
| multiflexi-csas-statement-tools | https://github.com/VitexSoftware/csas-statement-tools |
| multiflexi-discomp2abraflexi | https://github.com/Spoje-NET/discomp2abraflexi |
| multiflexi-docker | https://github.com/VitexSoftware/MultiFlexi |
| multiflexi-eu | https://multiflexi.eu |
| multiflexi-eu-mysql | https://multiflexi.eu |
| multiflexi-eu-sqlite | https://multiflexi.eu |
| multiflexi-eventor | https://multiflexi.eu/ |
| multiflexi-executor | https://multiflexi.eu/ |
| multiflexi-executor-azure | https://multiflexi.eu/ |
| multiflexi-executor-dev | https://multiflexi.eu/ |
| multiflexi-executor-docker | https://multiflexi.eu/ |
| multiflexi-executor-k8s | https://multiflexi.eu/ |
| multiflexi-executor-podman | https://multiflexi.eu/ |
| multiflexi-file2sharepoint | https://github.com/VitexSoftware/file2sharepoint |
| multiflexi-fiobank-statement-tools | https://github.com/Spoje-NET/fiobank-statement-tools |
| multiflexi-mail | https://github.com/VitexSoftware/multiflexi-mail |
| multiflexi-mail-ui | https://github.com/VitexSoftware/multiflexi-mail |
| multiflexi-migrations | https://github.com/VitexSoftware/multiflexi-database |
| multiflexi-mtr | https://github.com/VitexSoftware/multiflexi-mtr |
| multiflexi-pohoda-client-checker | https://github.com/Spoje-NET/pohoda-client-checker |
| multiflexi-pohoda-raiffeisenbank | https://github.com/Spoje-NET/pohoda-raiffeisenbank |
| multiflexi-pohoda-realpad | https://github.com/Spoje-NET/pohoda-realpad |
| multiflexi-probe | https://github.com/VitexSoftware/MultiFlexi |
| multiflexi-raiffeisenbank | https://github.com/VitexSoftware/multiflexi-raiffeisenbank |
| multiflexi-raiffeisenbank-statement-tools | https://github.com/VitexSoftware/raiffeisenbank-statement-tools |
| multiflexi-raiffeisenbank-ui | https://github.com/VitexSoftware/multiflexi-raiffeisenbank |
| multiflexi-realpad2mailkit | https://github.com/Spoje-NET/realpad2mailkit/ |
| multiflexi-redmine2abraflexi | https://github.com/VitexSoftware/Redmine2AbraFlexi |
| multiflexi-repocompare |  |
| multiflexi-scheduler | https://multiflexi.eu |
| multiflexi-sms-input | https://github.com/Spoje-NET/Sms-Input |
| multiflexi-subreg | https://github.com/Spoje-NET/subreg2abraflexi |
| multiflexi-subreg2abraflexi | https://github.com/Spoje-NET/subreg2abraflexi |
| multiflexi-tui | https://github.com/VitexSoftware/multiflexi-cli |
| multiflexi-web | https://github.com/VitexSoftware/MultiFlexi |
| multiflexi-zabbix | https://github.com/VitexSoftware/multiflexi-zabbix |
| multiflexi-zabbix-selenium | https://github.com/VitexSoftware/multiflexi-zabbix-selenium |

Please refer to the individual package documentation for more information.
