
# Install

pipenv https://pipenv-fork.readthedocs.io/en/latest/install.html

	sudo apt install python3-pip

	pip install --user pipenv
	mkdir -p src/rewards-sputnik
	cd src/rewards-sputnik/
	pipenv install requests
	export PATH=$PATH:/home/torsten/.local/bin
	pipenv install requests notebook

# Run

# create python env
torsten@torsten-HP-ZBook-15-G3:~/src/rewards-sputnik$ export PATH=$PATH:/home/torsten/.local/bin
torsten@torsten-HP-ZBook-15-G3:~/src/rewards-sputnik$ pipenv shell

# install Jupyter modules
((rewards-sputnik) ) torsten@torsten-HP-ZBook-15-G3:~/src/rewards-sputnik$ pipenv install plotly matplotlib pandas openpyxl

# run notebook
((rewards-sputnik) ) torsten@torsten-HP-ZBook-15-G3:~/src/rewards-sputnik$ jupyter notebook
