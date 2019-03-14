xv6 is a learning OS Kernel. It completely decribes the basic working of a UNIX based system.</br>
This is a reference guide for understanding and adding system calls in the kernel. 
</br>
<a href="https://builtvisible.com/the-ubuntu-installation-guide/">Here</a> is a complete guide to install Ubuntu.</br>
To start off first we must have git on our laptops to clone the official repo of xv6 by MIT.</br>
Git install command:

  <b>sudo apt-get install git</b></br>

Commands to install qemu (an emulator) and cloning the xv6 repo:</br></br>
<b>
  sudo apt-get install qemu</br>
  sudo apt-get install libc6-dev:i386</br>
  git clone https://github.com/mit-pdos/xv6-public.git xv6</br>
  chmod 700 -R xv6</br>
</b></br>
Test whether xv6 is running by running the following:</br></br>
<b>
  cd xv6</br>
  make</br>
  make qemu</br>
</b></br>
Congragulations, you've successfully installed xv6 on your computer!
</br>
Now, a system call is the programmatic way in which a computer program requests a service from the kernel of the operating system it is executed on. 
A system call is a way for programs to interact with the operating system.</br>
Video references to begin with:
<ul>
<li>For <a href="https://www.youtube.com/watch?v=21SVYiKhcwM">ps (a system call for listing process ID's)</a>
</li>
<li>For <a href="https://youtu.be/ny56yjshACY">cp (a system call for copying files)</a>
</li>
<li>For <a href="https://youtu.be/hIXRrv-cBA4">adding and changing priority</a> of processes.
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

I have uploaded a zip file of my project after adding these system calls.
</br>
To run my project, download the zip file, extract and run the <b>make</b> commands given above.
</br>Enjoy!
