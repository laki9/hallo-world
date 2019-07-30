 source build/envsetup.sh
 ANDROID_COMPILE_WITH_JACK=false breakfast dream2lte
 ANDROID_COMPILE_WITH_JACK=false brunch dream2lte
 
 lineage15.1 解决jack-server出错的问题
 1、全剧关闭jack（在VMware station中进行编译），编译成功（上述命令，添加环境变量）
 2、或许可以增加虚拟机的内存到16g，但是我的电脑只有8g，所以没有进行验证
 lineage16.0 会有is_same_v的问题，此函数属于c++17 is_same_v = is_same<T, U>::value; (since C++17) Inherited from std::integral_constant Member constants val..............



