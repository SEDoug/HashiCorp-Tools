# HashiCorp-Tools
Infrastructure Automation with HashiCorp  ( ͡° ͜ʖ ͡°)
<li><b>Vagrant</b> is a tool for building and managing virtual machine environments in a single workflow.</li>
  <li><b>Terraform</b> is a tool for building, changing, and versioning infrastructure safely and efficiently.</li>
<li><b>Vault</b> Secures, stores & tightly controls access to tokens, passwords, certificates, API keys & other secrets.</li>
<li><b>Packer</b> is easy to use and automates the creation of any type of machine image.</li>

## Install Latest Vagrant on Ubuntu 18.04 Desktop | CentOS | Debian 10 | Kali Linux
<li><a href="http://doug-macgregor.webflow.io/"</a>Installing HashiCorp-Vagrant-on-Ubuntu-18-04-Desktop</li>
#Some interesting finds trying to get vagrant up on this box.
# - If you happened to create a Vagrant project with just vagrant init (which I did).. this will create the Vagrantfile, but it won't have a box defined.
#- Instead, try this:
#$ vagrant init hashicorp/precise32
#$ vagrant up

#The Vagrant website has a Getting Started which gives some good examples.

#IMAGES coming

<li><a href="http://doug-macgregor.webflow.io/"</a>Installing HashiCorp-Vagrant-on-CentOS</li>
<li><a href="http://doug-macgregor.webflow.io/"</a>Installing HashiCorp-Vagrant-on-Debian-10</li>
<li><a href="http://doug-macgregor.webflow.io/"</a>Installing HashiCorp-Vagrant-on-Kali-Linux</li>

<!---
https://computingforgeeks.com/install-latest-vagrant-on-ubuntu-18-04-debian-9-kali-linux/
--->

## Commands: Upgrade Vagrant to 2.0.3 so you can install the plugin: run the following
<li><a>wget -c https://releases.hashicorp.com/vagrant/2.0.3/vagrant_2.0.3_x86_64.deb</a></li>
<li>sudo dpkg -i vagrant_2.0.3_x86_64.deb</li>
<li>vagrant plugin install vagrant-azure</li>

<!---Install Vagrant Azure Plugin & --->

## Links for Git, Vagrant, Python and Visual Studio Code
<li><a href="https://git-scm.com/download/linux"</a>Download GIT for Linux and Unix</li>
<li><a href="https://blog.scottlowe.org/2017/12/11/using-vagrant-with-azure/"</a>Using Vagrant with Azure</li>
