## Create and activate Virtual environment
```
apt install python3-venv
cd /opt/fortiwlc_telemetry/
python3 -m venv venv-ansible-2.9
source venv-ansible-2.9/bin/activate
```

## 3. Install pip and its requirements
```
sudo apt install python3-pip
python3 -m pip install -r pip_requirements.txt
```

## Run playbook
```
ansible-playbook play_config_system.yml
```