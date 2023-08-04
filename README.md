# SB_TSSSR_Checkpoint_scripting

## Version avec interaction utilisateur    
configurationReseau.txt   

#!/bin/bash   

echo "Rentrer successivement les informations suivantes : Nom du PC, adresse mac, adresse IP :"   
read -p "Nom du PC: " nom_pc   
read -p "Adresse MAC: " adresse_mac   
read -p "Adresse IP: " adresse_ip   

echo -e "Merci d'avoir entré les informations suivantes :"   
echo "Nom du PC    : $nom_pc"   
echo "Adresse MAC  : $adresse_mac"   
echo "Adresse IP   : $adresse_ip" >> configurationReseau.txt

# Version avec arguments    
configurationReseauArguments.sh

#!/bin/bash   

echo "Merci d'avoir entré les informations suivantes :"   
echo "Nom du PC    : $1"   
echo "Adresse MAC  : $2"   
echo "Adresse IP   : $3" >> configurationReseau.txt   
​
