# Pre-requirements

To go through this tutorial you will need:

1. Bash client: can be [bash on Windows](https://docs.microsoft.com/en-us/windows/wsl/install-win10) (Ubuntu distribution) 

2. Install Kubectl. For this example's purpose, follow [Install with snap on Ubuntu](https://kubernetes.io/docs/tasks/tools/install-kubectl/#on-linux-using-bash) 
```
sudo snap install kubectl --classic
kubectl version
```
3. Install Azure CLI V2. For this example's purpose, follow [Install with apt package manager](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest)
```
echo "deb [arch=amd64] https://packages.microsoft.com/repos/azure-cli/ wheezy main" | \
     sudo tee /etc/apt/sources.list.d/azure-cli.list

sudo apt-key adv --keyserver packages.microsoft.com --recv-keys 52E16F86FEE04B979B07E28DB02C46DF417A0893
sudo apt-get install apt-transport-https
sudo apt-get update && sudo apt-get install azure-cli
```

