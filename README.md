# minerd_installer
git clone https://github.com/stefanpabstme/minerd_installer.git && cd minerd_installer/ && chmod +x install.sh && ./install.sh

# CHECK which AND SETUP START ON REBOOT
which minerd

crontab -e

@reboot /usr/local/bin/minerd -a cryptonight -o stratum+tcp://monero.stefanpabst.me:4444 -u 43XueY8i77k7pQWm63n6QyTZApFZXd3vxKYKBkocCTZmUz3LvQUmCYo6BVQu63yenufVDU7QYMtp4619SJkKXCYhEmDE1wW.WORKERID -p x -t 1
