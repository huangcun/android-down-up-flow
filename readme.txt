���ֻ���޸ĵ��ļ�����git diff�����Ĳ����ļ�������hello-android.patch��hello-kernel.patch
�����������ļ��ı��޸��ļ�����Դ�����<�����ļ�����Դ���>Ŀ¼

android�����ļ���
#       external/hello/Android.mk
#       external/hello/hello.c
#       frameworks/base/core/java/android/os/IHelloService.aidl
#       frameworks/base/services/java/com/android/server/HelloService.java
#       frameworks/base/services/jni/com_android_server_HelloService.cpp
#       hardware/libhardware/include/hardware/hello.h
#       hardware/libhardware/modules/hello/Android.mk
#       hardware/libhardware/modules/hello/hello.c
#       packages/experimental/ExerciseHello/
packages/experimental/ExerciseHello
������ AndroidManifest.xml
������ Android.mk
������ res
��?? ������ drawable
��?? ��?? ������ icon.png
��?? ������ layout
��?? ��?? ������ main.xml
��?? ������ values
��??     ������ strings.xml
������ src
    ������ luo
        ������ hello
            ������ Hello.java

android�޸��ļ���
#       modified:   frameworks/base/Android.mk
#       modified:   frameworks/base/services/java/com/android/server/SystemServer.java
#       modified:   frameworks/base/services/jni/Android.mk
#       modified:   frameworks/base/services/jni/onload.cpp

kernel�����ļ���
#       drivers/hello/
drivers/hello/
������ hello.c
������ hello.h
������ Kconfig
������ Makefile

kernel�޸��ļ���
#       modified:   drivers/Kconfig
#       modified:   drivers/Makefile