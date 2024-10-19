# azure-cli
run azure cli for create image or vm

# Create Fedora VM

az vm create --resource-group Fedora --name myvm --image tunnelbiz:fedora:fedoraupdate:40.0.0 --size Standard_B1s --public-ip-sku Basic --authentication-type all --generate-ssh-keys --admin-username azureuser --admin-password SoMePaSsWoRd1 

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/tunnelbiz.fedora)

# Create rocky linux 9

az vm create --resource-group Fedora --name myvm --image tunnelbiz:rocky_linux:rocky9:9.4.1 --size Standard_B1s --public-ip-sku Basic --authentication-type all --generate-ssh-keys --admin-username azureuser --admin-password SoMePaSsWoRd1 

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/tunnelbiz.rocky_linuxrocky9)

# Create Centos 9 Stream 

az vm create --resource-group Fedora --name myvm --image tunnelbiz:rocky_linux:rocky9:9.4.1 --size Standard_B1s --public-ip-sku Basic --authentication-type all --generate-ssh-keys --admin-username azureuser --admin-password SoMePaSsWoRd1 

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/tunnelbiz.centos9)
