Thanks to [Ippsec's parrot-build](https://github.com/IppSec/parrot-build) for the foundation.
** Make sure to pip install ansible, apt has an older copy **

# Instructions
* Start with a fresh installation of [Kali Linux](https://www.kali.org/get-kali/)
* Install Ansible (python3 -m pip install ansible)
* Clone and enter the repo (git clone)
* ansible-galaxy install -r requirements.yml
* Make sure we have a sudo token (sudo whoami)
* ansible-playbook main.yml
