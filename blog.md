## 一些简单的linux命令 
#### 增： 
- mkdir xxx 创建新的文件夹 
- touch xxx 更新文件，如果文件不存在，则创建同名文件 
- echo 要增加的内容 > xxx 往文件里增加内容，如果文件内存在内容，则覆盖存在的内容； 如果文                           件不存在，则创建同名文件并添加内容
- echo 要增加的内容 >! xxx 强制往文件里增加内容 
- echo 要增加的内容 >> xxx 在文件的内容后增加内容
#### 改： 
- mv xxx yyy 将xxx重名为yyy，若yyy存在，则把xxx移动到yyy（移动或重命名文件） 
- cp xxx yyy 将xxx复制到yyy（复制文件） 
- cp -r xxx yyy 将xxx复制到yyy（复制文件夹） 
#### 删： 
- rm xxx 删除文件 
- rm -f xxx 强制删除文件 
- rm -r xxx 删除文件夹 
- rm -rf xxx 强制删除文件夹
#### 查：
- ls 显示当前目录下的文件 
- ls -a 显示当前目录下的所有文件 
- ls -la 显示当前目录下的所有文件及其详细信息
#### 其他一些命令：
- cd xxx/yyy 进入xxx/yyy路径 
- cd .. 返回上一级路径 
- cd - 返回上一次的路径 
- ~ 显示用户路径 
- ↑或!! 选择上一次使用的命令
- alt+. 选择上一次使用命令的参数
- xxx;yyy 先执行xxx命令，再执行yyy命令 
- xxx && yyy 先执行xxx命令，如果xxx命令执行成功，再执行yyy命令
