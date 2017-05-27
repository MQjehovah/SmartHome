编译指令  
make clean && make APP=1 SPI_SIZE_MAP=6 BOOT=new  
烧写参数  
0x00000      \bin\boot_v1.6.bin  
0x01000      \bin\upgrade\user1.4096.new.6.bin  
0x3fc000     \bin\esp_init_data_default.bin  
0x3fe000     \bin\blank.bin  
添加plug.c完成智能插座相关程序