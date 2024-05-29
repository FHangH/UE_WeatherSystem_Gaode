### 项目编译后打开崩溃，崩溃日志包含关键词：TSR

问题来源：UltraDynamicSky

解决方法：

 1. 修改 DefaultEngine.ini
    ![image](https://github.com/FHangH/UE_WeatherSystem_Gaode/assets/49579735/c0115739-1ff4-4fce-944e-1c7fa0637499)
 2. 修改后可以正常进入UE编辑器
 3. 找到 ProjectSetting -> render -> Default Feature Anti Aliasing
 4. 将 TSR 换成其他的选项
 5. 修改完后，应该就可以正常打开关卡了
