[ Execute all in command line interface ]  
[ Download script ]  
    
    wget https://raw.githubusercontent.com/Docushield/ipfs_setup_cli/main/ipfs.sh


[ Make script executable ]  
     
    sudo chmod +x ~/ipfs.sh


[ Run Script ]  
     
    ~/ipfs.sh

[ Autostart ]
    
    echo $'@reboot root /usr/local/bin/ipfs daemon &' > /etc/cron.d/docushield

