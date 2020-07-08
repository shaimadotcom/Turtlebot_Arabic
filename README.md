# Turtlebot_Arabic

# <div dir="rtl">قبل تثبيت تيرتل بوت</div>  
## <div dir="rtl"> اولا يجب انشاء مساحة عمل فيROS</div>

#### <div dir="rtl">اكتب الأمر التالي:</div> 
``` $ mkdir -p ~/catkin_ws/src ```
 ``` $ cd ~/catkin_ws/ ```
``` $ catkin_make ```  
#### <div dir="rtl">وتوثيق التثبيت الجديد من خلال أمر:</div>
``` $ source devel/setup.bash ```

# <div dir="rtl"> تثبيت تيرتلبوت</div>  


#### <div dir="rtl">تنصيب الاعتماديات </div>

``` cd ~/catkin_ws/src/ ``` 

 ``` git clone https://github.com/ROBOTIS-GIT/turtlebot3_msgs.git ``` 
 
``` git clone https://github.com/ROBOTIS-GIT/turtlebot3.git ```

``` cd ~/catkin_ws && catkin_make ```


### <div dir="rtl">لدى تيرتل بوت ثلاث نماذج,يجب اختيار واحد منها قبل عملية الإطلاق:</div>

##### <div dir="rtl">اذهب إلى الملف من خلال أمر:</div>
``` gedit ~/.bashrc ```
##### <div dir="rtl">وفي نهاية الملف اضف هذا السطر مع نموذج اللذي اخترته:</div>
``` export TURTLEBOT3_MODEL=burger ```
``` export TURTLEBOT3_MODEL=waffle ```
``` export TURTLEBOT3_MODEL=waffle_pi ```


#### <div dir="rtl">أعد تحميلbashrc </div>
``` source ~/.bashrc ```

##### <div dir="rtl">لتحميل ملفات محاكاة التيرتل بوت اجري هذه الأوامر:</div>
``` cd ~/catkin_ws/src/ ```

``` git clone https://github.com/ROBOTIS-GIT/turtlebot3_simulations.git ```

``` cd ~/catkin_ws && catkin_make ```

=========================================
========================================


