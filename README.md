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

MultiFlexi
----------

All included applications are ready to run in the [MultiFlexi](https://multiflexi.eu) environment.
See the full list of ready-to-run applications within the MultiFlexi platform on the [application list page](https://www.multiflexi.eu/apps.php).

[![MultiFlexi App](https://github.com/VitexSoftware/MultiFlexi/blob/main/doc/multiflexi-app.svg)](https://www.multiflexi.eu/apps.php)



## Packages included

| Name | URL |
|------|-----|
| multiflexi | https://github.com/VitexSoftware/MultiFlexi |
| multiflexi-abraflexi-client-check | https://github.com/VitexSoftware/php-abraflexi-config |
| multiflexi-abraflexi-contract-invoices | https://github.com/VitexSoftware/abraflexi-contract-invoices |
| multiflexi-abraflexi-digest | https://github.com/VitexSoftware/AbraFlexi-Digest |
| multiflexi-abraflexi-email-importer | https://github.com/VitexSoftware/AbraFlexi-email-importer |
| multiflexi-abraflexi-kimai-importer | https://github.com/VitexSoftware/Kimai2AbraFlexi/settings |
| multiflexi-abraflexi-mailer | https://github.com/VitexSoftware/php-abraflexi-mailer |
| multiflexi-abraflexi-matcher | https://github.com/VitexSoftware/php-abraflexi-matcher |
| multiflexi-abraflexi-pricefixer | https://github.com/VitexSoftware/AbraFlexi-pricefixer |
| multiflexi-abraflexi-raiffeisenbank | https://github.com/VitexSoftware/abraflexi-raiffeisenbank |
| multiflexi-abraflexi-reminder | https://github.com/VitexSoftware/abraflexi-reminder |
| multiflexi-abraflexi-revolut | https://github.com/VitexSoftware/AbraFlexi-Revolut |
| multiflexi-abraflexi-tools | https://github.com/VitexSoftware/AbraFlexi-Tools |
| multiflexi-api | https://github.com/VitexSoftware/MultiFlexi |
| multiflexi-discomp2abraflexi | https://github.com/Spoje-NET/discomp2abraflexi |
| multiflexi-fiobank-statement-downloader | https://github.com/VitexSoftware/fiobank-statement-downloader |
| multiflexi-pohoda-client-checker | https://github.com/Spoje-NET/pohoda-client-checker |
| multiflexi-pohoda-raiffeisenbank | https://github.com/Spoje-NET/pohoda-raiffeisenbank |
| multiflexi-raiffeisenbank-statement-downloader | https://github.com/VitexSoftware/raiffeisenbank-statement-downloader |
| multiflexi-raiffeisenbank-statement-tools | https://github.com/VitexSoftware/raiffeisenbank-statement-tools |
| multiflexi-realpad2mailkit | https://github.com/Spoje-NET/realpad2mailkit/ |
| multiflexi-redmine2abraflexi | https://github.com/VitexSoftware/Redmine2AbraFlexi |
| multiflexi-sms-input | https://github.com/Spoje-NET/Sms-Input |
| multiflexi-subreg2abraflexi | https://github.com/Spoje-NET/subreg2abraflexi |
| multiflexi-zabbix | https://github.com/VitexSoftware/MultiFlexi |

Please refer to the individual package documentation for more information.
