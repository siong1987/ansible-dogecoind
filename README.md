# ansible-dogecoind

![](https://raw.github.com/siong1987/ansible-dogecoind/master/ansible-dogecoind.png)

Run dogecoind on your server of choice to the moon. Designed for Ubuntu 13.10 x64 with at least 1GB memory.

## Installation

### Digital Ocean

Create a [droplet](https://www.digitalocean.com/) on digital ocean and note the IP Address with your SSH key.

Then on your local machine, run the following.

```
git clone https://github.com/scottmotte/ansible-dogecoind.git
cd ansible-dogecoind
cp dogecoin.conf.example dogecoin.conf
cp hosts.example hosts
```

Edit the `dogecoin.conf` and `hosts` files.

Deploy using [ansible](http://www.ansibleworks.com). (install instructions for ansible are in [requirements](#requirements) below.

```
ansible-playbook playbook.yml -i hosts
```

That's it. Now dogecoind is running on its own server.

## Requirements

[Ansible](http://www.ansibleworks.com/) is required.

## Shibes

- [Scott Motte](https://github.com/scottmotte) `DJEBk3QoBGbNL7oWzXqvjgW1A9DuFKHs8q`
- [Teng Siong Ong](https://github.com/siong1987) `DCzU75twZRfhLmVSEtG8M62ENj7Yy9yYm9`