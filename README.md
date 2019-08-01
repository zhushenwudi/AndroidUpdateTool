# Android增量更新工具 -- bsdiff与bspatch
  bsdiff -- 生成patch文件  
  bspatch -- 合并new.apk
  
# 使用方法(mac)
  解压后 : make  
  生成增量文件 : ./bsdiff old.apk new.apk patchfile.patch  
  增量文件和old.apk合并成新的apk : ./bspatch old.apk new2.apk patchfile.patch
  
# 通过命令行将patch导入手机
  adb push patchfile.patch /sdcard/
