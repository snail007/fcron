# fcron
Linux下cron的替代者，支持秒周期级别的任务  
fcron-3.2.0-fixed-time-can-less-than-10-seconds  
fcron-3.2.0版，官方的设置执行周期小于10秒的时候会报错，无法执行任务。此为修复版，执行周期可以小于10秒。  
#安装步骤
tar xzvf fcron-3.2.0-fixed-time-can-less-than-10-seconds.tar.gz  
cd fcron-3.2.0  
./configure --prefix=/usr  --sysconfdir=/etc --without-sendmail  
make  
make install  

#编辑任务
fcrontab -e

#任务格式写法
http://fcron.free.fr/doc/en/fcrontab.5.html  





