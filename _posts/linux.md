ctrl z fg #复原
pushd popd #路径栈操作
1-20行批量添加#
> :1,20s/^/#/g

批量删除
> :1,20s/#//g

清除高亮
:nohlsearch

> du -h --max-depth=1 /path