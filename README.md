### Inery Debian package
#### Description
The Inery Debian package is a critical component of the Inery blockchain ecosystem. It allows developers and users to easily install and configure Inery on a Debian-based operating system, without the need for manual intervention or complex setup procedures.

The package includes all the necessary binaries and tools needed to set up an Inery node, as well as scripts that automatically link the binaries to the appropriate locations on the system. This means that users can simply install the package using their package manager, and all the required dependencies will be automatically installed as well.

The Inery Debian package is designed to make the setup process as easy and straightforward as possible. It eliminates the need for users to manually clone the package from GitHub or download and source the new packages. Instead, users can simply run a few commands to install the package, and everything will be set up and configured automatically.

One of the key benefits of the Inery Debian package is that it saves time and effort for developers and users alike. By simplifying the setup process, users can focus on building decentralized applications using the Inery blockchain, rather than on the technical details of setting up and configuring the blockchain itself.

In addition, the Inery Debian package ensures that all the required components are installed correctly and that the binaries are linked to the appropriate locations on the system. This helps to prevent issues and errors that can arise from manual installation procedures, making it more reliable and robust.

Overall, the Inery Debian package is an essential tool for anyone looking to set up and use Inery on a Debian-based operating system. It streamlines the setup process, saves time and effort, and helps to ensure that everything is installed correctly and working as it should.

#### Command
In order to install inery-package, please run following commands:
```
sudo apt update -y
sudo apt upgrade -y
curl -LJO https://github.com/inery-blockchain/inery-package/blob/master/inery-package_1.0.0_all.deb?raw=true -o inery-package_1.0.0_all.deb; sudo dpkg -i inery-package_1.0.0_all.deb
```