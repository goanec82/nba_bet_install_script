# nba_bet_install_script

#install

sudo apt install git -y && git clone https://github.com/goanec82/nba_bet_install_script && cd nba_bet_install_script/ && bash install && cd ~ && sudo rm -R nba_bet_install_script

#start

cd NBA-Machine-Learning-Sports-Betting/ && python3 main.py -xgb -odds=fanduel && cd ~

#Log command

cd NBA-Machine-Learning-Sports-Betting/ && echo `date +%d.%m.%Y`: `python3 main.py -xgb -odds=fanduel` >> templog.txt && cd ~
