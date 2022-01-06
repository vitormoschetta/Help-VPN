# Help-VPN

É possível conectar a um computador Windows, usando a conexão de Area de Trabalho Remota, a partir do Ubuntu? Sim:

Primeiro precisamos estar na mesma rede, isso é possível graças a ao uso de VPN. 

### Open VPN

Nas distribuições Linux podemos utilizar o Open VPN:
``` 
sudo apt-get install openvpn
sudo apt-get install network-manager-openvpn
sudo apt-get install network-manager-openvpn-gnome
``` 

Para se conectar, precisamos de um arquivo de extensão `.ovpn`:
```
  sudo openvpn --config client.ovpn
```  

  
