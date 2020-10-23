# Acer-Nitro5-AN515-54-58CL-CATALINA

EFI files to boot Catalina Hackintosh on Acer Nitro 5


<p align="center">
  <img src="https://i.ibb.co/wgdnvKJ/Captura-de-Tela-2020-10-21-a-s-21-08-31.png">
</p>


# Atualizando pelo Mojave

1. Faça download da atualização para o Catalina através do gerenciador de Atualizações de Software do OSX;
2. Faça download do repositório e extraia o arquivo Zip;
3. Abra a partição EFI do HD/SSD onde seu OSX Mojave está instalado;
4. Substitua a pasta EFI do seu HD/SSD pela pasta EFI do repositório;
5. Reinicie o seu Hackintosh e certifique-se de setar o Boot para o SSD/HD onde esta instalado o Mojave;
6. Inicie o processo de instalação/atualização do Catalina (passo 2);
7. A instalação/atualização irá exigir o reinício do seu Hackintosh Nitro5;
8. Bem-vindo ao Catalina!

# Instalação limpa

## Instruções

1. Baixe a ISO do macOS Catalina no site [Olarila](https://www.olarila.com/topic/6278-new-vanilla-olarila-images/);
2. Siga as instruções para [criar seu pendrive bootável](https://www.olarila.com/topic/5794-hackintosh-guide-install-macos-with-vanilla-olarila-image-step-by-step-install-and-post-install-windows-linux-or-mac/);
3. Após criar o pendrive bootável, monte a partição EFI do mesmo. Substitua a pasta EFI do pendrive pela pasta EFI que disponibilizei no repositório;
4. Altere o BOOT na BIOS para o seu pendrive e inicie o processo de Instalação (evite tocar o trackpad, isso irá causar bug que desativa o teclado, você irá precisar de um mouse USB);
5. Após instalação, inicie o macOS Catalina utilizando seu pendrive criado para instalação;
6. Abra as partições EFI do HD/SSD escolhido e do pendrive, através do Clover. Copie e substitua, se precisar, os arquivos do seu HD/SSD pelos arquivos contidos no pendrive (coloquei os arquivos contidos do EFI do meu pendrive na pasta PENDRIVE_BOOT_EFI, caso prefira usar o que eu utilizo);
7. Ejete o pendrive e reinicie o computador, altere o BOOT da BIOS para a partição do seu HD/SSD utilizado para instalação do macOS Catalina;
8. No menu do Clover, escolha iniciar o macOS Catalina, lembre-se de não encostar no trackpad/touchpad para não travar seu teclado, caso isso aconteça será necessário reiniciar o seu Nitro 5;
9. Use o Clover para montar as partições EFI do seu HD/SSD escolhido para instalação do macOS Catalina e substitua a pasta EFI da sua partição pela mesma pasta EFI que disponibilizei;
10. Reinicie o seu Hackintosh.

## Observações

Para evitar o bug do trackpad que inutiliza o teclado, utilize a combinação das teclas **Fn + F3** para desativar o trackpad do seu Acer Nitro 5, assim você pode usar seu teclado sem medo de encostar no trackpad.

Ainda não consegui fazer o trackpad ELAN do Acer modelo AN515-54-58CL funcionar.
Deixe um comentário caso encontre uma alternativa melhor para solucionar este problema.

Kext para Airport com placa wireless Intel adicionado. Usar aplicação Heliport para reconhecer as redes disponíveis (créditos: [Alexandre Lima](https://github.com/aclima01)).
- [Airport Kext](https://github.com/OpenIntelWireless/itlwm/releases/tag/v1.2.0-alpha);
- [Heliport App](https://github.com/OpenIntelWireless/HeliPort/releases/tag/v1.0.1)

## Roda ou não roda ?

- Placa de vídeo dedicada Nvidea ❌;
- Intel UHD Graphics 630  ✔️;
- Trackpad ❌;
- WebCam ✔️;
- Teclado ✔️;
- Audio ✔️;
- Rede Ethernet (limitado a 100Mbps) ✔️;
- Rede Wifi ✔️;
- Bluetooth ❌
