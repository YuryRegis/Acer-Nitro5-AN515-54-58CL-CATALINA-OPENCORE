# Acer-Nitro5-AN515-54-58CL-Catalina-OPENCORE

EFI files to boot Catalina Hackintosh on Acer Nitro 5


<p align="center">
  <img src="https://i.ibb.co/wgdnvKJ/Captura-de-Tela-2020-10-21-a-s-21-08-31.png">
</p>


# Substituindo o Clover Bootloader

1. Faça download do repositório e extraia o arquivo Zip;
2. Abra a partição EFI do HD/SSD onde seu OSX Catalina está instalado;
4. Substitua a pasta EFI do seu HD/SSD pela pasta EFI do repositório;
5. Reinicie o seu Hackintosh e certifique-se de setar o Boot para o SSD/HD onde esta instalado o Catalina;
6. Bem-vindo ao Catalina com Trackpad Apple Gestures e Audio otimizado!


## Observações

Kext para Airport `Itlw` para placa wireless Intel AX200 adicionado. Usar aplicação Heliport para reconhecer as redes disponíveis (créditos: [Alexandre Lima](https://github.com/aclima01)). Para inicia-lo automaticamente ao abrir o Catalina, adicione-o na lista de aplicativos em `itens de início` (Preferências do Sistema > Usuários e Grupos > Itens de Início).

<p align="center">
  <img src="https://i.ibb.co/ngft7VN/Captura-de-Tela-2020-10-23-a-s-00-54-39.png">
</p>

- [Heliport App](https://github.com/OpenIntelWireless/HeliPort/releases/tag/v1.0.1)

### Especificações do Hardware
INFO           | ESPECIFICAÇÃO
:------------- | :---------------------------------
Fabricante     | ACER BRASIL
Modelo         | NITRO 5 AN515-54-58CL
OS Fabrica     | Endless OS
BIOS           | v1.31
CPU            | Intel Core i5-9300H
iGPU           | Intel UHD Graphics 630
GPU            | GeForce GTX 1650 4 GB GDDR5 
HDD            | 1 TB 5400 RPM SATA III
SSD            | SSD de 128 GB M.2 SATA III (x2)
RAM            | 16 GB 2667 MHz DDR4 (2x8GB)
Wifi+Bluetooth | Intel AX200 (INT9560)
Ethernet       | Realtek RTL8168/8111 PCI-E Gbit
Audio          | Realtek ALC255 
Trackpad       | ELAN 0504

## Roda ou não roda ?

- Placa de vídeo dedicada Nvidea ❌;
- Intel UHD Graphics 630  ✔️;
- Trackpad (Apple gestures) ✔️;
- WebCam ✔️;
- Teclado ✔️;
- Audio (OTIMIZADO) ✔️;
- Rede Ethernet (limitado a 100Mbps) ✔️;
- Rede Wifi ✔️;
- Bluetooth ❌
