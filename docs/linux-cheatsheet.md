## 文件目录
ls -la 列出所有文件
mkdir test 当前目录下创建文件夹
cd test 转到当前目录下的test文件夹
touch test.py 创建test文件
cp test.py test2.py 复制test
mv 移动文件或者转移文件
rm 删除文件
cd .. 回到上一级
rm -rf 删除文件夹 -r表示递归，-f表示强制
## 查看与搜索
echo "hello liunx" >demo.txt 创建demo并写入hello linux
cat demo.txt 打印demo的内容
grep "hello" demo.txt 在demo中找hello
find . -name "*txt" 从当前目录下寻找名字包含txt的
## 进程与系统
ps aux|head 显示进程占用
top 
df -h 显示磁盘用量
free -h