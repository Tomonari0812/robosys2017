# robosys2017

#robosys2017の課題

#徐々にLEDが明るくなったり暗くなったりする

#使い方

  1.$make
  2.$sudo insmod myled.ko
  3.$sudo chmod 666 /dev/myled0
  $echo 2 > /dev/myled0 
  $sudo rmmod myled
  $make clean
