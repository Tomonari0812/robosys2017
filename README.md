# robosys2017の課題


#徐々にLEDが明るくなったり暗くなったりする

#使い方
  $make
  $sudo insmod myled.ko
  $sudo chmod 666 /dev/myled0
  $echo 2 > /dev/myled0 
  $sudo rmmod myled
  $make clean
