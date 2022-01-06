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

Saiba mais:

<https://qastack.com.br/server/103926/is-there-a-real-way-to-connect-to-watchguards-vpn-from-linux>



### Remmina

Remmina é um client UI para acesso remoto. Com ele podemos nos conectar a uma máquina da mesma rede

Segue post sobre Remmina:

<https://linuxkamarada.com/pt/2020/04/11/conexao-de-area-de-trabalho-remota-do-windows-no-linux-com-clientes-rdp/#.Ydc8DnXMJqM>
