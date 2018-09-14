# Instalando via dpkg
!!! warning "Versão 0.1"

     Essa é uma versão básica para servir de referencia para amigos que estão começando.

## Antes de começar

Nos exemplos eu vou usar o sistema operacional Debian.

Para acompanhar você precisa estar usando um sistema baseado no Debian

## Podemos instalar via DPKG

### Obtendo o Virtualbox
Vamos para o link
```sh
 https://www.virtualbox.org/wiki/Linux_Downloads
```

<a class="example-image-link" href="https://greenmind.top/abase/CDN/Vm-distros.png" data-lightbox="example-1">
  <img class="example-image" src="https://greenmind.top/abase/CDN/thumbVm-distros.png" alt="image-1" />
</a>


Nesse caso vou usar o Debian Jessie 64 Bits
```sh
 http://download.virtualbox.org/virtualbox/5.1.10/virtualbox-5.1_5.1.10-112026~Debian~jessie_amd64.deb
```

#### Buscando por outras versões
Caso queira usar uma outra versão antiga podemos usar também o seguinte link
```sh
https://download.virtualbox.org/virtualbox/
```

Também podemos ver um pouco sobre as versões disponíveis 
```sh
    VirtualBox 5.2 (active maintenance)
    VirtualBox 5.1 (no longer supported, support ended 2018/04)
    VirtualBox 5.0 (no longer supported, support ended 2017/05)
    VirtualBox 4.3 (no longer supported, support ended 2015/12)
    VirtualBox 4.2 (no longer supported, support ended 2015/12)
    VirtualBox 4.1 (no longer supported, support ended 2015/12)
    VirtualBox 4.0 (no longer supported, support ended 2015/12) 
```

## Iniciando a instalação
Nesse exemplo estou no diretório
```sh
 /home/greenmind/Downloads
```

Para instalar preciso fazer
```sh
# dpkg -i virtualbox-4.3_4.3.40-110317~Debian~wheezy_amd64.deb
```

## Tudo vai estar OK! Senão estiver
Se tudo estiver certo o virtualbox já vai estar instalado , mais tem maquinas que precisam de alguns requisitos pré instalados , caso precise vai aparecer uma mensagem para você fazer um (apt-get -f install).

Tem pessoas que preferem por ser mais rápido , eu prefiro instalar tudo da seguinte forma.

```sh
# apt-get install gcc make
# apt-get install linux-headers-3.16.0-4-amd64
# apt-get install linux-headers-amd64
```

Após retorne a executar a instalação

<a class="example-image-link" href="https://greenmind.top/abase/CDN/Instalacao_VirtualBox_Linux_DPKG.png" data-lightbox="example-1">
  <img class="example-image" src="https://greenmind.top/abase/CDN/thumbInstalacao_VirtualBox_Linux_DPKG.png" alt="image-1" />
</a>


Após isso o Virtualbox vai estar instalado
```sh
Menu de aplicativos -> Sistema -> Oracle VM VirtualBox
```

## Referencias
[Linux Donwload] (https://www.virtualbox.org/wiki/Linux_Downloads)

[Old Builds] (https://www.virtualbox.org/wiki/Download_Old_Builds)