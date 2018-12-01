If you are trying to make a project in xv6, the most basic to start with is by adding system calls to the kernel.
It is necessary to have a Linux flavor for this.

To start off first we must have git on our laptops to clone the official repo of xv6 by MIT.
Git install command:

  sudo apt-get install git

Commands to install qemu (an emulator) and cloning the xv6 repo:

  sudo apt-get install qemu</br>
  sudo apt-get install libc6-dev:i386
  git clone https://github.com/mit-pdos/xv6-public.git xv6
  chmod 700 -R xv6

Test whether xv6 is running by running the following:

  cd xv6
  make
  make qemu
  
Congragulations, you've successfully installed xv6 on your computer!

Now, a system call is the programmatic way in which a computer program requests a service from the kernel of the operating system it is executed on. 
A system call is a way for programs to interact with the operating system.

Video references to begin with:
<ul>
<li>For <a href="https://www.youtube.com/watch?v=21SVYiKhcwM">ps (a system call for listing process ID's)</a>
</li>
<li>For <a href="https://youtu.be/ny56yjshACY">cp (a system call for copying files)</a>
</li>
<li><a href="https://youtu.be/hIXRrv-cBA4">For adding and changing priority of processes.</a>
</li>
<li>For changing the default RR scheduer to a simple <a href="https://youtu.be/DZ0-GMtOtEc">Priority scheduler</a>
</li>
</ul>
Some other references:
<ul>
<li>For adding <a href="https://medium.com/@silvamatteus/adding-user-programs-to-xv6-ba9896605942">clear</a> (a system call to clear the terminal)
</li>
<li>For adding <a href="https://medium.com/@silvamatteus/adding-new-system-calls-to-xv6-217b7daefbe1">shutdown</a> (a system call to shutdown xv6)
</li>
</ul>
