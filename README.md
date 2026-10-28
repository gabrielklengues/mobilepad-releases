# MobilePad Companion — downloads

Use o navegador do celular como controle touch de Super Nintendo, PS2 ou Arcade
para jogos e aplicativos que aceitam teclado no Windows. O Companion recebe
os comandos pela rede local e permite configurar as teclas de cada jogador.
Jogos, ROMs, BIOS e emuladores não acompanham o programa.

## Baixar e instalar

Os instaladores disponíveis ficam em [Releases](https://github.com/gabrielklengues/mobilepad-releases/releases).
Uma versão só está disponível para download quando sua release contém o
arquivo `MobilePad-Companion-<versão>-win-x64-setup.exe`, o checksum `.sha256`
e o manifesto `companion-update.json`. Se ainda não houver releases com esses
arquivos, não há uma versão publicada para instalar.

O programa requer Windows 10 ou posterior, x64. A instalação é por usuário,
com atalhos e desinstalador, e inclui os runtimes necessários. O jogador não
precisa instalar Node.js ou o SDK .NET.

A primeira instalação que habilita as atualizações pelo aplicativo é manual:
baixe o setup de uma release e execute-o. Se já estiver usando uma instalação
anterior, feche-a antes de atualizar. Depois, o Companion pode avisar sobre
novas versões, baixar o instalador e pedir confirmação para instalar e reiniciar.
Adiar a atualização permite continuar jogando.

Atualizações e desinstalação preservam os perfis e as credenciais protegidas
em `%LOCALAPPDATA%/MobilePad`. Após reiniciar o Companion, os celulares precisam
conectar e ser autorizados novamente.

## Sobre este repositório

Este repositório público contém somente downloads e metadados de releases.
Os fontes próprios do MobilePad permanecem privados. Perfis, códigos de
pareamento, tokens e credenciais dos jogadores não pertencem a este repositório.
As licenças e os avisos dos componentes de terceiros acompanham o instalador.
