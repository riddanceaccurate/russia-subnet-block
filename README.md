# Russia Subnet Blocking

How to block Russia (RU) subnets / ranges and a complete list of IP address with a script to block using Uncomplicated FireWall (UFW) 

## Dependencies

[ufw](https://wiki.ubuntu.com/UncomplicatedFirewall)

Uncomplicated Firewall (ufw) is a frontend for iptables and is particularly well-suited for host-based firewalls. ufw provides a framework for managing netfilter, as well as a command-line interface for manipulating the firewall.

## Installation

Clone the repository.

```bash
git clone https://github.com/riddanceaccurate/russia-subnet-block.git
```
Go into the folder

```bash
cd russia-subnet-block
```
Ensure permissions for script are correct for installation

```bash
chmod +x ru-block.sh 
```

## Usage

Run the script on your server or computer with UFW

```bash
./ru-block.sh 
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[GPL-3.0](https://choosealicense.com/licenses/gpl-3.0/)
