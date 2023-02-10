# yamaha
①tftpの許可  
tftp host any  

②コンフィグファイルの生成  
cat RT1 config > RT1.config  

③コンフィグの上書き  
tftp  
tftp> connect  
(to) 192.168.100.1  
tftp> binary  
tftp> put RT1.config config/  
tftp> q  
