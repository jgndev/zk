
Azure Cloud Shell is a command-line environment for managing resources in Azure through the browser. This makes it possible to do any command-line management on any device that has a web browser installed.

Azure Cloud Shell also provides [[Cloud Storage]] to persist files like SSH keys, scripts and more. The storage attached to Cloud Shell is limited to only one region.

This includes an editor that can be used to make changes to files stored in your Cloud Shell environment.

The Virtual Machine that backs your Cloud Shell session always has the latest version of PowerShell and Bash.

## Access Methods

Direct Link: https://shell.azure.com

Azure Portal:
![A screenshot of Cloud Shell accessed from Azure portal.](https://learn.microsoft.com/en-us/training/modules/intro-to-azure-cloud-shell/media/access-cloud-shell-from-azure-portal.png)


## Available Shell Types

You can choose between [[PowerShell]] or [[Bash]] when launching Cloud Shell.


## Inactivity Expiration

Cloud Shell sessions terminate after 20 minutes of inactivity. When a session terminates the files on your [[Cloud Drive]] are persisted but you need to start a new session to access the Cloud Shell environment again.

## Upload and Download

You can upload and download files while in your Cloud Shell session.

![A screenshot of how to access CloudDrive in a Cloud Shell session.](https://learn.microsoft.com/en-us/training/modules/intro-to-azure-cloud-shell/media/use-azure-cloud-drive.png)

## Cloud Shell Tools

Several tools are pre-installed in Cloud Shell

Linux tools:

bash, zsh, sh, tmux, dig

Azure tools:

Azure CLI, AzCopy, Azure Functions CLI, Service Fabric CLI, Batch Shipyard, blobxfer

Text editors:

code, vim, nano, emacs

Source control:

git

Build tools:

make, maven, npm, pip

Containers:

Docker Machine, kubectl, Helm, DC/OS CLI

Databases:

MySQL client, PostreSQL client, sqlcmd, mssql-scripter

Other:

iPython client, Cloud Foundry CLI, Terraform, Ansible, Chef InSpec, Puppet Bolt, HashiCorp Packer, Office 365 CLI

