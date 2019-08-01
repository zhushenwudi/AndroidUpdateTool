# Android增量更新工具 -- bsdiff
  生成patch文件
  
# 使用方法(mac)
  ./bsdiff old.apk new.apk patchfile.patch
  
# 通过命令行将patch导入手机
  adb push patchfile.patch /sdcard/
