# jzwq

#realsence工程注意事项
1. 创建64位程序，32位程序链接realsence库报错
2. 创建工程后头文件引用realsence的include路径，库路径引用realsence x64路径、第三方glfw库路径(debug文件夹下)
3. 链接设置需引用如下库
glu32.lib
opengl32.lib
realsense2.lib
glfw-imgui.lib

