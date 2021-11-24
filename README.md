
# Install

We use pipenv https://pipenv-fork.readthedocs.io/en/latest/install.html

  196  sudo apt install python3-pip

	# changed my mind about global install; you can sip this
  	197  pip install notebook
  	202  pip uninstall notebook

  203  pip install --user pipenv
  205  mkdir -p src/rewards-sputnik
  206  cd src/rewards-sputnik/
  207  pipenv install requests
  209  export PATH=$PATH:/home/torsten/.local/bin
  210  pipenv install requests
  212  pipenv install notebook

# Run

# create python env
torsten@torsten-HP-ZBook-15-G3:~/src/rewards-sputnik$ export PATH=$PATH:/home/torsten/.local/bin
torsten@torsten-HP-ZBook-15-G3:~/src/rewards-sputnik$ pipenv shell

# install Jupyter modules
((rewards-sputnik) ) torsten@torsten-HP-ZBook-15-G3:~/src/rewards-sputnik$ pipenv install plotly matplotlib pandas openpyxl

# run notebook
((rewards-sputnik) ) torsten@torsten-HP-ZBook-15-G3:~/src/rewards-sputnik$ jupyter notebook
