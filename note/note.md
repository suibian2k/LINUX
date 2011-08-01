# about peter

## peter note
+	122.115.61.189/tmp/cc-note
+	http://happypeter.github.com/LGCB
+	https://github.com/happypeter/cc-note.git

## get peter's config
+	goto www.github.com serch peter-vim	

## get peter's hen
+	https://github.com/happypeter/hen.git

## we listen from peter 
+	ww.akae.cn
+	The art of unix programming
+	http://vim-showoff-peter.heroku.com
+	http://happypeter.github.com/GitBeijing/vim-conf-share.html
+	K&R
+	linux+c+python
+	progit
+	 linux.vbird.org

# linux

## script language
+	usually is interpreter language
+	run some fucntions of a specific program
+	needn't defined

## windows and linux
+	GUI-Command Line
+	Case sensitive
+	\r\n => newline int the windows
+	\n => newline in the linux

## path
+	abs path
+	rel path => unsafe

## system file tree

## install tig
1.	http//jonas.nitro.dk/tig/releases/
2.	./cinfigure
3.	make
4.	sudo make install

# markdown

## use markdown
+	
	1.	markdown(/bin/filename) f1 > f2
	2.	firefox xx.html

+	markdown xx	=> xx xx清空

## __bold__ ,_italic_

# equipment
## /dev/fb0 : monitor
1.	sudo chmod 777 /boot/grub/grub.cfg
2.	vim /boot/grub/grub.cfg
3.	find linux /boot/vm.....	
	>at the end add 'vga=0x318'

## /dev/input/mice : mouse

# shorcuts
+	 ctrl+alt+shift+f1 :  
	>enter console
+	 alt+f7  
	>leave console

# <tab>
+	bash completion

# copy and paste
1.  selected
2.  middle mouse button

# ./ ../

# bash command

## run the C file
1.  cc .c
2.  ./a.out

## view history
+	history

## normal command
+	zip 
	+	 unzip +.zip
+	gz 
	+	 tar xzvf +.gz
+	rm
+	rm -rf
+	rmdir
+	rmdir -p
+	mkdir
+	mkdir -p：mkdir -p ll/ss
+	touch
+	vim
+	cp
+	wget
+	ls 
+	ls -l
+	ls -ld
+	ls -a 
	+	 hidden files
+	whoami
	+	find user
+	pwd
	+	find the file folder
+	mv
+	cd
## find the file location
+	1.  find . |grep file-name :	get from the hard disk
	2.  locate file-name 		: 	get from the database of it,  
		24 hours a time 

+	find . |grep +regular_expresstion

+   find . -exec 'grep' {} + | grep -i peter +    
	+	 find a file named contains 'peter'

## modify the file permissions 
+	sudo chmod Octal(+x) file 

## modify the file name
+	mv ：mv aa bb

## ctrl+d or exit

## ldd a.out
+	display link library

## dpkg -S path
+	sudo apt-get install package_name
    
## gcc 
+	gcc -I/path/to/header/

+	gcc main.c -l hello
    +   gcc others-files file.c

+	gcc 
	+	 redefined

+   gcc -Wall file-name 
    +   warning

+   gcc -g
    +   gdb

## gdb 
+   gdb fn
    +   start
    +   r(run)
        +   r+argument

    +   l(list)
    +   n(next)
    +   p(list) 
    +   s(step)
    +   <enter>  
        again upline
    +   c(continue)
    +   q(quit)
    +   b(break)  
        set breakpoints
        +   info break

    +   file
    +   continue

### process
+  `set follow-fork-mode child` 
+   



## >
+	redirect , store

## |
+	pipeline
+   ./app |less

## script
+	echo

    for file in file1 file2 file3
	do
		echo $file
	done

+   shor_name=\`echo $file|awk -F(set separator)'.'{print $1}\`
	+	-F	:	set separator
    +   `   :   statement 

## process
+	ps 
	+	 find process

+	ps aux|grep -i(case sensitive)  firefox

+	kill 9 process_number 
	+	 9 forced to kill

# BASH command-line-shortcuts
+   ctrl+a  HOME
    +   Move to beginning of line

+   ctrl+e  END
    +   Move to end of line 

+   ctrl+left-arrow
    +   Move forward a word

+   ctrl+right-arrow
    +   Move backward a word

+   ctrl+w
    +   delete forward a word

+   esc+d
    +   delete backward

+   ctrl+u
    +   delete to beginning of line

+   ctrl+u
    +   delete to end of line

---------------------------------------------------------
# sh
+   source fn.sh
    +   don't copy another process
+   sh fn.sh
+   ./fn.sh
----------------------------------------------------
## vim
+	vim + several files name

### insert mode
+	esc
+	jj(customize)

##.snippet file
+	.vim/snippet

+	
	snippet+	ww
	tab www

+	$+{tigital} 
	+	 where is the cursor

+   fun,inc,wh,pr,for,if
    +   tab to next select

### vim command
+	operator + number + motion

+	hlkj

+	A 
	+	 to the end of the line

+	gg(G) 
	+	 to the first(end) of the page

+	w 
	+	 to a word

+	p 
	+	 paste

+	yy 
	+	 copy a line

+	dG 
	+	 delete to the end

+	cc 
	+	 modify the line

+	x 
	+	 delete

+	s 
	+	 midify

+	u,ctrl-r,U 
	+	 undo

+	a 
	+	 after the shift and change the mode

+	cw 
	+	 midify

+	shift+v 
	+	 line select

+	v

+	ctrl+v 
	+	 vertical select

+	r 
	+	 redo

+	ctrl+t,ctrl+d 
	+	 indentation(insert mode)

+	ctrl+n 
	+	 filled the identifier

+	ctrl+x+l 
	+	 filled the line

+	ctrl+x+k 
	+	 filled the word base on dictionary

+	ctrl+x+f 
	+	 filled the name of file which in the current folder

+	move up 
	+	 ctrl+p

+	move down 
	+	 ctrl+n

+	2dd，dw，d$,dd 
	+	 delete command

+	2cw c2e 
	+	 midify command

+	/word enter

+	:wq 
	+	 save and exit

+	:w name 
	+	 named in the file

+	:q! 
	+	 no save and exit

+	:bd  
	+	 close

+	:DiffSaved 
	+	 difference between memory and hard dive  
	 and open two windows

+	:e file_name 
	+	 open the file

+	:new 
	+	 creat a new file

+	:ls 
	+	 display current buffer

+	zx 
	+	 open fold

+	zf 
	+	 create fold 

+	zc 
	+	 close fold

+	ctrl+c 
    +    notes

+   ctrl+x
    +    drop notes

+	,t 
	+	 display frame

+	,e 
	+	 open vimrc

+	,n 
	+	 display directory

+	tab 
	+	 switch several files

+   ctrl+p
    +   fill keyword

+   ctrl+x
    +   format

### ctags
+	ctags hello.c dd.c

+	vim .c

+	ctrl+] 
	+	 from call to find definition

+	ctrl+o 
	+	 from definition to find call

+	vim -t function_name 
	+	 need tags, locate the function

+	gd 
	+	 get local definition

+	gD 
	+	 get global 

+   ctrl+n

### cscope

###  ".vimrc" under home
+   map and so on
    +   map ,ss :setlocal spell!<cr> =>  
        ,ss replace :setlocal spell!<cr>
+   set nu :   
    when vim start config

+	set autoindent

+	set nu

+	,ss 
	+	 check the word error

+   set nonu

### split view
+   vim -On file1 file2
    +   Vertival Split

+   vim -on file file ..
    +   Horizontal Split

+   Ctrl+w+s 
    +   Vertival Split own

+   Ctrl+w+v
    +   Horizontal Split

+   Ctrl+w+c
    +   close

+   Ctrl+w+q
    +   close

+	Ctrl+w+w
	+	 switch

+	vimdiff 
	+	 two windows
+   ,,
    +   quit

### the help of vim
+	:h vim-modes
+	：h 
+	：help

#### tutorial for vim
+	vimtutor (in bash)
+	man vim

#### the command in insert mode for help 
+	:h i ctrl+n

#### switch with bash
+   :! command
    +   in vim
-------------------------------------------------------------
## arm
+   nfs
    +   sudo apt-get install nfs-kev...
    +   sudo /etc/init.d/nfs-kev......

+   PATH
    1.   "vim .bashrc"
    2.    export PATH=$PATH:/home/xwp/tmp/usr/local/arm/4.4.1/bin

+   link 
    1.  minicom
    2.  <enter>
    3.  bridged  
    4.  ip 192.168.1.200
    5.  /home/xwp/nfs
    6.  mount -t nfs -o nolock,tcp 192.168.1.200:/home/xwp/nfs /mnt

+   gcc lib
    1.  ./configure --host=arm-linux --target=arm-linux 
    2.  make

+   /etc/profile
    export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:../jpeg-8/.libs:
    export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:../freetype-2.3.11/objs/.libs:
---------------------------------------------------------------
+   file fn;
