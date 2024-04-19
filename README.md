# Automatic Certificate Renewals

## RCL SSL AutoRenew Function

The RCL SSL AutoRenew Function is a Microsoft Azure Function app that automatically renews SSL/TLS certificates created in the RCL SSL Portal.

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Frcl-ssl%2Frcl-ssl-automatic-renewal%2Fmain%2Fazuredeploy.json)

You can use the function app to automatically renew SSL/TLS certificates created in the RCL SSL Portal using the the following creation options :

- Azure Key Vault + DNS (including SAN)
- Azure App Services

[Read the documentation](https://docs.rclapp.com/autorenew/autorenew.html)

## RCL SSL HTTP AutoRenew

RCL SSL HTTP AutoRenew can be run as a Linux Daemon or a Windows Service in the web hosting machine for automatic certificate renewal. It is installed in the hosting machine. It provides the following functionality :

- automatically renew certificates created in the RCL SSL Portal using the Stand Alone (including SAN) option using the HTTP Challenge type
- save SSL/TLS certificates in the hosting machine for a web server to use

[Read the documentation](https://docs.rclapp.com/httpautorenew/httpautorenew.html)

## RCL SSL DNS AutoRenew

RCL SSL DNS AutoRenew can be run as a Linux Daemon or a Windows Service in the web hosting machine for automatic certificate renewal.

You can use RCL SSL DNS AutoRenew to automatically renew SSL/TLS certificates created in the RCL SSL Portal using the the following creation options :

- Azure DNS (including SAN)

Certificate are saved on the hosting machine for a web server to use

[Read the documentation](https://docs.rclapp.com/dnsautorenew/dnsautorenew.html)
