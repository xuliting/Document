* cmake环境都用Build/Tools 下的工具:

  Build/Tools/linux 编译car工具，选择linux_devtools(use cmake)；用于在linux上编译ARM android clang环境；

  Build/Tools/mac 编译car工具，选择mac_devtools; 用于在mac上编译ARM android clang环境；

  目前新的编译方式，Car工具不分 ARM、x64，只分mac、linux；Car工具不生成机器码，不区分ARM、x86；

  Build/Tools是新的cmake环境的，对应linux和mac；Tools_32、Tools_64是旧环境的，都是linux的可执行文件。

* 旧的car工具的编译环境:

  linux_32 和 arm_android的car 工具编译环境一样：devtools_32;
