أولا قم بإنشاء حساب على [DigitalOcean](https://cloud.digitalocean.com/registrations/new). يجب وضع معلومات بطاقة بنكية ماستر كارد سيتم سحب مبلغ 5 دولارات وإعادته إلى الحساب بعد عشر دقائق, سيتم إعطاؤك رصيد مجاني بمبلغ 200 دولار لمدة 60 يومًا.


بعد الدخول الى حسابك على digitalocen قم بالاتي  
![step 1](images/digitalocen1.PNG)
![step 2](images/digitalocen2.PNG)
![step 3](images/digitalocen3.PNG)
![step 4](images/digitalocen4.PNG)
بعد ذلك قم بـ اعادة كل الخطوات فقط قم بتغيير الرقم السري و الـ hostname ضعه بـ اسم thehive




ثم يجب انشاء جدار حماية لمنع أي اتصالات خارجية واضافة كل من  wazuh and thehive
 كالاتي:
 ![step 5](images/firewall1.png)
![step 6](images/firewall2.PNG)
![step 7](images/firewall3.PNG)
![step 8](images/firewall4.PNG)
![step 9](images/firewall5.PNG)




بعد ذلك قم بـ الدخول على صفحة موجه الأوامر في جهازك وكتابة 
ssh root@0.0.0.0 
ضع ال IP addres الخاص ب wazuh or thehive بدلا من الصفر سيطلب منك الرقم السري الذي وضعته اثناء انشاء Droplets

  بعد الدخول لكي تتمكن من التثبيت والتعديل ستجد جميع أوامر التنزيل مرفقة في الملفات 


  
 _____________________________________________________________________________________________________________________________

 الآن قم بتحميل [wazuh](https://documentation.wazuh.com/current/installation-guide/wazuh-agent/wazuh-agent-package-windows.html) على جهاز ويندوز في VirtualBox أو VMware

في هذا الفيديو طريقة تعيين الويندوز كـ Wazuh Agent وإنشاء تنبيهات ضارة باستخدام [mimikatz](https://github.com/gentilkiwi/mimikatz)

https://drive.google.com/file/d/1xwYfbziJ8AYq_1u9Yy6PdV-JQNwrQTBA/view?usp=sharing

   
