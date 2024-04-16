cmake ../mangos -DCMAKE_INSTALL_PREFIX=~/cmangos/run -DBUILD_EXTRACTORS=ON -DPCH=1 -DDEBUG=0 -DBUILD_PLAYERBOTS=ON -DBUILD_AHBOT=ON -DBUILD_ELUNA=ON -DBUILD_SOLOCRAFT=ON

### ubuntu 22.04
提示缺少lreadline，安装
apt install libreadline-dev

### liblua52.a
到dep/lualib/lua文件夹下复制

### libshared.a
到
