# device_driver  
  
# for Raspberry Pi3  
  GPIOの25番ピンに接続したLEDをタイマー機能を使用し点滅させるデバイスドライバです。  
    
## Install  
  $git clone https://github.com/FumihiroUeki/device_driver.git  
  $cd device_driver  
  $make  
  $sudo insmod myled.ko  
  
## Uninstall
  $sudo rmmod myled
