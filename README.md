# Windows Test Environment
This template will deploy:
- Virtual network, consisting of a default subnet and a network security group to restrict inbound RDP traffic to our local machine
- Windows Server 2019 virtual machine, configured as a domain controller
- Windows 10 virtual machine, configured as a domain-joined workstation

Inspired by: [Infrastructure as Code in practice: Building a Blue Team lab with Bicep](https://joshua-lucas.com/building-a-blue-team-lab-with-bicep/)

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FKiZach%2FWindows-Test-Environment%2Fmaster%2Fazuredeploy.json)