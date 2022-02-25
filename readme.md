       install node version mangager and switching node version in linux



sudo apt install curl

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash

vi bashrc

nvm

nvm install --lts

nvm ls-remote

nvm install <that version shown in nvm ls-remote>

nvm ls                                     ------> shows the version installed in node

nvm use <that version in nvm ls>           ------> to switch to the version  

finally nexe package supports in node version v10.16.0