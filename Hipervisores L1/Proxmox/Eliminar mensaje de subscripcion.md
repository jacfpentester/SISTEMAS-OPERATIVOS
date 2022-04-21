cd /usr/share/javascript/proxmox-widget-toolkit  
cp proxmoxlib.js proxmoxlib.js.bak  
nano proxmoxlib.js  
Ext.Msg.show({  
  title: gettext('No valid subscription'),  
Cambiar por:  
void({ //Ext.Msg.show({  
  title: gettext('No valid subscription'),  
  Reiniciamos el servicio, pero recomiendo reiniciar la maquina  
  systemctl restart pveproxy.service
