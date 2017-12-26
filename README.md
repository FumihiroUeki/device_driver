# device_driver  
  
# for raspberry pi3  
  GPIOの25番号ピンに接続したLEDをタイマを使用し点滅させるデバイスドライバです。  
    
## Install  
  $git clone https://github.com/FumihiroUeki/device_driver.git  
  $cd device_driver  
  $make  
  $sudo insmod myled.ko  
  
## Uninstall
  $sudo rmmod myled
