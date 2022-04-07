### Instalar shellcheck o o cualquier paquete que te aparece pero no descarga  
- Buscamos el paquete del repo  AUR en la siguiente URL: https://aur.archlinux.org/   
- Copiamos el enlace Downloas snapshot que esta en el menu de la derecha.  
- En el Terminal descargamos el paquuete con: wget URLQUECOPIAMOS.  
- Descomprimimos con: tar -xvf nombredelarchivo.tar.gz  
- Entramos en el directorio y ponemos: makepkg -Acs
- En el caso de shellcheck me dio 2 archivos comprimidos uno extension xz y otro zst.  
- Ejecutamos: sudo pacman -U  nombredelpaquete.pkg.tar.zst  
- Y ya quedo instalado en el caso del shellcheck me fue con el zst pero quizas otros paquetes se hagan con xz.
