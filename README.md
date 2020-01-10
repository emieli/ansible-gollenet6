## Download repository
```
cd /etc/ansible
git clone https://gitlab.golle.org/emel02/ansible_gollenet6.git gollenet6
```

## Create and activate Virtual environment
```
apt install python3-venv
python3 -m venv venv-ansible-2.9
source venv-ansible-2.9/bin/activate
```

## Install pip and its requirements
```
cd /etc/ansible/gollenet6
sudo apt install python3-pip
python3 -m pip install -r pip_requirements.txt
```

## Run playbook
```
cd /etc/ansible/gollenet6
ansible-playbook play_config_system.yml
```