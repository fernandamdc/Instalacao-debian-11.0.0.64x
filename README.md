# Instalacao-debian-11.0.0.64x

1- Coloquei uma musica para da uma relaxada;(Ruth B. - Dandelions (Audio)

2- pesquisei Debian download 11;(entrei em um monte de site errado) mas acertei no final.

3- Acessei o primeiro site oficial:  https://www.debian.org/CD/http-ftp/

4-Opção: Imagens oficiais de CD/DVD da versão "estável (stable)".

5-Para instalar o Debian em uma máquina sem conexão com a Internet, é possível usar as imagens de CD (700 MB cada) ou as imagens de DVD (4,4 GB cada). Baixe o primeiro arquivo de imagem de CD ou DVD, grave-o usando um gravador de CD/DVD (ou um pendrive USB, nos portes i386 e amd64), e então reinicialize a partir dessa mídia..
 
6-Acessei  a primeira opção amd64 (Que serve para processadores de 64bit, sendo ele ADM ou INTEL).

7-Que me levou a um link onde estava tudo em inglês: https://cdimage.debian.org/debian-cd/current/amd64/iso-cd/ no final do site havia os links para download da iso disponiveis,onde selecionei o link : debian-11.0.0-amd64-netinst.iso

INSTALAÇÃO DENTRO DO VIRTUAL BOX.

8- Instalei o virtualbox um dia antes de executar a instalação, Cliquei  em  NOVO, selecionei a quantidade de megas 2000.

9- Criei um novo disco rígido virtual agora; Selecionei Tipo de arquivo de disco rígido: VDI (VirtualBox Disk Image); logo em seguida  Armazenamento em disco rígido físico: Dinamicamente alocado e por fim a Localização e tamanho de arquivo: localização já escolhida pelo virtual box tamanho já definido 8,00GB.

10- Acrescentei a Iso do Debian 11, clique em próximo, automaticamente o sistema já me disponibilizou.

11-INICIAR O SISTEMA DEBIAN E CONFIGURAR:

- Para instalar sem a interface gráfica cliquei na opção "install".
- Linguagem: Português > Brasil.
- Aguardar carregamento.
- Nome da máquina: DebianMental.
- Nome de domínio: (pode ser deixado em branco).
- Senha do root : 1234 ex.
- Confirmar senha:
- Nome completo para novo usuário: Fernanda Mendes.
- Nome de usuário para sua conta: Fernandinha.
- Senha para novo usuário: 1234 ex.
- Selecione sua localização para horário.
- Particionamento de disco: Assistido - Usar o disco inteiro.
- Selecione o disco a ser particionado: enter.
- Esquema de particionamento: todos os arquivos em uma partição(para iniciantes).
- finalizar o particionamento e escrever as mudanças no disco.
- Mostra as mudanças e pergunta se deseja escrever: SIM.
- Pergunta se quer ler a mídia: NÃO.
- País do espelho do repositório Debian: Brasil.
- Espelho do repositório debian - Servidor FTP para realizar o download dos pacotes.
- Informações sobre proxy HTTP: deixe em branco.

ESCOLHER OS SOFTWARES A SEREM INSTALADOS:

- Ambiente da área de trabalho.
- Servidor SSH.
- Utilitários do sistema padrão.
- Instalar o carregador de Inicialização GRUB no seu disco primário? SIM (Pois caso contrário o sistema operacional não irá rodar.)
- Onde deseja instalar: partição no qual está instalado o sistema operacional.
- INFORMA QUE A INSTALAÇÃO ESTÁ COMPLETA: -CONTINUAR-

INICIALIZAÇÃO DA MÁQUINA

Inicialização automática caso você não faça escolha.
Mostra o usuário e solicita senha.
 
