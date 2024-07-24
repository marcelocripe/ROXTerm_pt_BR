Repositório oficial do programa "ROXTerm" (atual)

https://github.com/realh/roxterm

Repositório oficial do programa "ROXTerm" (antigo)

https://sourceforge.net/p/roxterm/code/ci/master/tree/


Traduções revisadas por marcelocripe:

https://github.com/marcelocripe/ROXTerm_pt_BR/blob/main/roxterm_pt_BR.po

https://github.com/marcelocripe/ROXTerm_pt_BR/blob/main/roxterm.desktop

Para utilizar o arquivo "roxterm_pt_BR.po" e o "roxterm.desktop", inicie o Emulador de Terminal na pasta onde estão os arquivos que foram baixados.

"roxterm_pt_BR.po":

Comando para converter o arquivo editável da tradução com a extensão ".po" para ".mo".

$ msgfmt roxterm_pt_BR.po -o roxterm.mo

Comando para copiar o arquivo da tradução com a extensão ".mo" para a pasta do idioma "pt_BR".

$ sudo cp roxterm.mo /usr/share/locale/pt_BR/LC_MESSAGES

"roxterm.desktop":

Comando para copiar o arquivo com a extensão ".desktop" para a pasta /usr/share/applications.

$ sudo cp roxterm.desktop /usr/share/applications

Comando para escrever globalmente todas as entradas dos menus do antiX:

$ sudo desktop-menu --write-out-global
