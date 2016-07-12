# Django-tutorial

python3 virtualenvwrapper install

http://www.marinamele.com/2014/07/install-python3-on-mac-os-x-and-use-virtualenv-and-virtualenvwrapper.html

virtualenvwrapper doc

http://virtualenvwrapper.readthedocs.io/en/latest/

1) ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

2) brew install python3

3) sudo easy_install pip

4-1) pip install virtualenvwrapper 에러가난다면

4-2) sudo pip install --ignore-installed virtualenvwrapper

* brew로 깔아서 그렇대

* python3.x 쓸 경우 pip3로 깔아야된다는 말이 있음

5-1) (testEnv) Mac-mini:local user$ vi ~/.bash_profile

   export WORKON_HOME=/Users/user/Documents/Dev/temp/virtualenv

   export VIRTUALENV_PYTHON=/usr/local/bin/python3.5

   source /usr/local/bin/virtualenvwrapper.sh
   
5-2) virtualenv 초기셋팅 하고 mkvirtualenv --python=/usr/local/bin/python3.5 testEnv

6) pip install Django
