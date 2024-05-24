# ansible-setup

##### Fedora

	sudo dnf install git ansible

##### Ubuntu

	sudo apt install git ansible

---

##### Clone the repo

	git clone https://github.com/szabopeter1/ansible-setup.git ~/.setup


##### Change directory to playbook's directory

	cd ~/.setup

---

##### Fedora

	ansible-playbook -K fedora-setup.yml

##### Ubuntu

	ansible-playbook -K ubuntu-setup.yml