# <h2>Configuração do virtualizador Proxmox</h2></br>
![alt text](https://www.proxmox.com/images/proxmox/Proxmox_logo_standard_hex_400px.png)</br></br></br>
🌡 Instalação e configuração do virtualizador <b>Proxmox</b>

Proxmox VE é uma plataforma completa de gerenciamento de servidor de código aberto para virtualização empresarial. Ele se integra perfeitamente ao hipervisor KVM e aos contêineres Linux (LXC), armazenamento definido por software e funcionalidade de rede, em uma única plataforma. Você pode obter mais detalhes no site da ferramenta: https://www.proxmox.com/en/. </br>Uma duvida que muitos tem a respeito da ferramento é sobre as subscrições, por exemplo vou ter alguma limitação se não assinar o suporte. 
A resposta é não, nenhuma limitação em questão de funcionalidades, o diferencial é que com assinatura de suporte é que os pacotes são mais testado e ficam no diretoria enterprise.

Iremos apresentar a ferramenta desde a forma mais basica. Como instalação configuração de rede, discos.</br>


Para demonstração da ferramenta iremos utilizar o virtualbox para construção dos laboratorios, porém isso não deve ser usado em produção.
Nessa primeira abordagem vamos criar a maquina virtual onde iremos instalar de forma basica o PVE.
 Link para download do virtualbox: </br>
 
 https://www.virtualbox.org/wiki/Downloads 
 
 Configuração da maquina que iremos criar no Virtualbox:</br>
 memoria: 4gb</br>
 processador: 2 nucleos</br>
 hd: 20</br>
 rede: modo bridge
 modo promisco da placa: permitir tudo
 
 
 Link para dowload do PVE
 
 https://www.proxmox.com/en/downloads/category/iso-images-pve
 
