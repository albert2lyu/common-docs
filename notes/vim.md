
### centos7 ����vim8

```
yum remove vim -y
yum install ncurses-devel -y
git clone https://github.com/vim/vim.git
cd vim/src

��Makefile
CONF_OPT_PYTHON = --enable-pythoninterp

make
make install
#���û�����������`/etc/profile`,���һ��д��
PATH=$PATH:/usr/local/bin/
```

���֮ǰû��python֧�֣�����python֧�֣�����Ҫ���±���

```
cd vim/src
make distclean
./configure --enable-pythoninterp=yes --with-python-config-dir=/usr/lib/python2.7/config
make
make install
```

### ��װ�ļ������nerdtree

��������� http://www.vim.org/scripts/script.php?script_id=1658

github�� https://github.com/scrooloose/nerdtree

```
git clone https://github.com/scrooloose/nerdtree.git ~/.vim/bundle/nerdtree
```