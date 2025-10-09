O passo a passo a seguir mostra como instalar a gerência da controladora RAID no Linux.

1º Verifique se o servidor tem acesso a internet, importante para instalar os pacotes.
```bash
ping google.com

```
2º Instalação dos pacotes necessários.

```bash
apt update && apt instal unzip alien -y
```

3º Baixar o pacote da MegaRaidCli

```bash
wget https://docs.broadcom.com/docs-and-downloads/raid-controllers/raid-controllers-common-files/8-07-14_MegaCLI.zip

```

4º Precisamos descompactar o arquivo pois o mesmo vem zipado.

```bash
sudo unzip 8-07-14_MegaCLI.zip

```

5º Após descompactar precisamos gerar o pacote para Debian, pois o mesmo vem com .rpm
Entre na pasta Linux que vou criada ao descompactar o arquivo.

```bash
cd Linux
sudo alien MegaCli-8.07.14-1.noarch.rpm

```

6º Instalar pacote .deb

```bash
sudo dpkg -imegacli_8.07.14-2_all.deb

```

7º Após instalado você pode executar a ferramenta com a opção -h para obter ajuda.

```bash
/opt/MegaRAID/MegaCli/MegaCli64 -h

```
