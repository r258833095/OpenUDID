OpenUDID
========

代替udid做设备唯一标识

使用方法把Open UDID 导入项目，在使用的地方，引入头文件，如下即可
 NSString* openUDID = [OpenUDID value];
 
【注意】#error This file uses the classic non-ARC retain/release model; hints below...
【解决方法】-fno-objc-arc
