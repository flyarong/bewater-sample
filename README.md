# bewater项目结构范例
## 更新与编译
```
git clone https://github.com/zhandouxiaojiji/bewater_sample.git
cd bewater_sample
make
```
## 运行test
cd proj/test/shell  
./run.sh test

## Tips
1.make会自动更新和编译所有子模块  
2.如果在编译skynet的时候报错缺readline.h  
sudo yum -y install readline-devel ncurses-devel  
3.如果在编译bewater的时候报错缺lcurl库  
sudo yum -y install curl-devel  

