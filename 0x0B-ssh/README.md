<img src="http://blogs.encamina.com/por-una-nube-sostenible/wp-content/uploads/sites/19/2019/01/ssh_header.jpg" style="height:100%;width:100%" />

# SSH

## Description

SSH, also known as Secure Shell or Secure Socket Shell, is a network protocol that gives users, particularly system administrators, a secure way to access a computer over an unsecured network.

SSH also refers to the suite of utilities that implement the SSH protocol. Secure Shell provides strong password authentication and public key authentication, as well as encrypted data communications between two computers connecting over an open network, such as the internet.

In addition to providing strong encryption, SSH is widely used by network administrators to manage systems and applications remotely, enabling them to log in to another computer over a network, execute commands and move files from one computer to another.

SSH refers both to the cryptographic network protocol and to the suite of utilities that implement that protocol. SSH uses the client-server model, connecting a Secure Shell client application, which is the end where the session is displayed, with an SSH server, which is the end where the session runs. SSH implementations often include support for application protocols used for terminal emulation or file transfers.

SSH can also be used to create secure tunnels for other application protocols, for example, to securely run X Window System graphical sessions remotely. An SSH server, by default, listens on the standard Transmission Control Protocol (TCP) port 22.

## Learning Objectives

- What is a server
- Where servers usually live
- What is SSH
- How to create an SSH RSA key pair
- How to connect to a remote host using an SSH RSA key pair
- The advantage of using #!/usr/bin/env bash instead of /bin/bash


#### Files
Files | Description |
-------- | ----------- |
**0-use_a_private_key** |Write a Bash script that uses ssh to connect to your server using the private key ~/.ssh/school with the user ubuntu|
**1-create_ssh_key_pair** |Write a Bash script that creates an RSA key pair.|
**2-ssh_config** |Your machine has an SSH configuration file for the local SSH client, let’s configure it to our needs so that you can connect to a server without typing a password. Share your SSH client configuration in your answer file.|
**100-puppet_ssh_config.pp** | Let’s practice using Puppet to make changes to our configuration file. Just as in the previous configuration file task, we’d like you to set up your client SSH configuration file so that you can connect to a server without typing a password.|

## Author

* **github** [jhonholberton](https://github.com/jhonholberton)
* **Linkedin:** https://www.linkedin.com/in/jhon-gonzalez-354487202