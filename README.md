# energi-MN-bash
Energi token Mansternode bash modif

Modified script to install NRG Masternode with manual Wallet info input


Step 1 - Create the wallet file and copy/paste your wallet informations in the UTC-123 file

  mkdir -p /home/nrgstaker/.energicore3/keystore/
  
  nano /home/nrgstaker/.energicore3/keystore/UTC-123
  
Step 2 - Run the install and leave blank when it's ask "Paste URL (leave blank and hit ENTER to do it manually):" : 
  bash -ic "$(wget -4qO- -o- https://raw.githubusercontent.com/atouloupis/energi-MN-bash/master/energi3-linux-installer.sh)" ; source ~/.bashrc  
 
 Step 3 - Accept all by pressing "enter" 2 times
