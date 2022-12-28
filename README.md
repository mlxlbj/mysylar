# sylar

# 转载于 https://github.com/sylar-yin/sylar.git

### 编译库
```
cd sylar
make 
make -j
```

### 使用库创建项目
sh generate.sh ${project-name} ${name-space}
cd ${project-name}
make
make -j
sh move.sh #编译完成后，move可执行文件和动态库
bin/${project-name} -s #执行

