#!/bin/bash

# Configuration timezone
echo "Configuration timezone"
timedatectl set-timezone America/Sao_Paulo

#Configurando memória swap
echo "Configuration swap memory"
wget https://raw.githubusercontent.com/osidney/Swap/master/swap.sh -O swap
sh swap 1G
