# Linux Guide For All

![linux](https://user-images.githubusercontent.com/40186859/158926847-3daddbe4-e97a-4ccd-8a51-a6aed12a32d2.png)

## What is Unix?

Unix comes before linux, so if you know a little bit, it will be great for you. Unix is an operating system whose development started in 1969 for multi-user, multi-tasking. Unix is not free and open source os. It can be only utilized by its copywriters. So linux came into the picture. E.g: SunOS, Solaris, SCO Unix, HP/UX.

## What is Linux?

To understand simply, like Windows, Mac, Linux is an operating system [OS] based on Linux Kernel. Operating systems lie between computer hardware and computer users, so that users can interact with computers easily. It was developed by Linus Torvalds in 1991.

It is free and open source means you can use it for free, view its source code. We can change the source code of linux and use it for personal as well as commercial purposes.

E.g: Ubuntu, Arch Linux, Debian GNU etc.

## Where is Linux?

* TV
* Mobile Phones
* Self Driving car
* Plane
* Rocket
* Many website are hosted on linux

## Who uses Linux?

* US Government
* Top Tech Companies like Google, Microsoft, Amazon by various means
* Hackers
* Financial Institutes
* Computer Programmers and Researchers
* Those who want to acquire high technical knowledge

## Some Linux Distro:

* Ubuntu
* Fedora
* Elementory OS
* Red Hat OS
* Cent OS
* Kali Linux
* Arch Linux

## Linux vs Windows

* Linux runs for months or years without reboot, but in windows often reboot is required.
* Linux is Free But Windows is Paid.
* Most of the software is available for windows but not in linux.
* Linux is Secure than windows.
* Linux is Fully Customizable but Windows is not.

![linux_vs_windows](https://user-images.githubusercontent.com/40186859/158927266-6a77af39-11cc-4cb7-9d91-9bed295c8d07.png)

## Points to Remember

* Folder in linux called directory.
* Linux is a case sensitive System. A is different than a.
* Avoid using filename as space.
* Super Admin is also called root who can do anything.
* Software is called a package.

## Are all linux based OS free?

No, not all linux based OS are free. Enterprise level linux based operating systems are paid. E.g Red Hat is a paid OS, if we have a problem the Red Hat team will support and provide us a solution.

## Basic Tour Of Ubuntu

* Background Change
* Datetime Settings
* Wifi
* Bluetooth, etc....

## Everyday Used Linux Commands

Command | Meaning  
--- | --- 
whoami | Your current user name.
hostname| Your current host name.
pwd | Print working directory.
ls | List directory contents.
ls -l | List directory contents in long format.
touch | Create a file.
cat | Concatenate files and print on output i.e. read file.
users | Display currently logged in users.
cp | Copy file. E.g: cp file1.txt file2.txt 
mv | Move file. E.g: mv file1.txt file2.txt 
mkdir | Create a directory. E.g: mkdir work 
rmdir | Remove directory. E.g: rmdir work 
rm | Remove files or directory.
rm -R | Remove directory will contain all content.
cd | Change directory.
cd .. | One step back.
touch ch{1..9}.txt | Create file ch1 to ch9.
rm ch* | Delete all files starting from ch.
locate | find your file by name \[Fast\]. sudo updatedb 
sudo | Forcefully do a job. 
find | Find or search in file. \[Slow\]. E.g find -name "brp.txt"
date | Show date and time
sudo reboot | Restart computer
clear | Clear screen

## User Management Command In Linux
Command | Meaning  
--- | --- 
sudo passwd `username` | Change password of user.
useradd `username`| Add new user without home directory.
useradd -m `username`| Add new user with home directory.
userdel `username` | Delete user without his/her user directory.
userdel -r `username` | Delete user with his/her user directory.
groupadd `groupname` | Add new user group.
groupdel `groupname` | Delete user group.
usermod -aG `groupname` `username` | Add user to group.
su `username` | Switch to specific user.
id `username` | Display user and group information.

## Files
- /etc/passwd => to get user lists.
- /etc/group => to get groups details.
- /etc/shadow => to get hash password.

## Obscure but useful

- `expr`: perform arithmetic or boolean operations or evaluate regular expressions

- `m4`: simple macro processor

- `yes`: print a string a lot

- `cal`: nice calendar

- `env`: run a command (useful in scripts)

- `printenv`: print out environment variables (useful in debugging and scripts)

- `look`: find English words (or lines in a file) beginning with a string

- `cut`, `paste` and `join`: data manipulation

- `fmt`: format text paragraphs

- `pr`: format text into pages/columns

- `fold`: wrap lines of text

- `column`: format text fields into aligned, fixed-width columns or tables

- `expand` and `unexpand`: convert between tabs and spaces

- `nl`: add line numbers

- `seq`: print numbers

- `bc`: calculator

- `factor`: factor integers

- [`gpg`](https://gnupg.org/): encrypt and sign files

- `toe`: table of terminfo entries

- `nc`: network debugging and data transfer

- `socat`: socket relay and tcp port forwarder (similar to `netcat`)

- [`slurm`](https://github.com/mattthias/slurm): network traffic visualization

- `dd`: moving data between files or devices

- `file`: identify type of a file

- `tree`: display directories and subdirectories as a nesting tree; like `ls` but recursive

- `stat`: file info

- `time`: execute and time a command

- `timeout`: execute a command for specified amount of time and stop the process when the specified amount of time completes.

- `lockfile`: create semaphore file that can only be removed by `rm -f`

- `logrotate`: rotate, compress and mail logs.

- `watch`: run a command repeatedly, showing results and/or highlighting changes

- [`when-changed`](https://github.com/joh/when-changed): runs any command you specify whenever it sees file changed. See `inotifywait` and `entr` as well.

- `tac`: print files in reverse

- `comm`: compare sorted files line by line

- `strings`: extract text from binary files

- `tr`: character translation or manipulation

- `iconv` or `uconv`: conversion for text encodings

- `split` and `csplit`: splitting files

- `sponge`: read all input before writing it, useful for reading from then writing to the same file, e.g., `grep -v something some-file | sponge some-file`

- `units`: unit conversions and calculations; converts furlongs per fortnight to twips per blink (see also `/usr/share/units/definitions.units`)

- `apg`: generates random passwords

- `xz`: high-ratio file compression

- `ldd`: dynamic library info

- `nm`: symbols from object files

- `ab` or [`wrk`](https://github.com/wg/wrk): benchmarking web servers

- `strace`: system call debugging

- [`mtr`](http://www.bitwizard.nl/mtr/): better traceroute for network debugging

- `cssh`: visual concurrent shell

- `rsync`: sync files and folders over SSH or in local file system

- [`wireshark`](https://wireshark.org/) and [`tshark`](https://www.wireshark.org/docs/wsug_html_chunked/AppToolstshark.html): packet capture and network debugging

- [`ngrep`](http://ngrep.sourceforge.net/): grep for the network layer

- `host` and `dig`: DNS lookups

- `lsof`: process file descriptor and socket info

- `dstat`: useful system stats

- [`glances`](https://github.com/nicolargo/glances): high level, multi-subsystem overview

- `iostat`: Disk usage stats

- `mpstat`: CPU usage stats

- `vmstat`: Memory usage stats

- `htop`: improved version of top

- `last`: login history

- `w`: who's logged on

- `id`: user/group identity info

- [`sar`](http://sebastien.godard.pagesperso-orange.fr/): historic system stats

- [`iftop`](http://www.ex-parrot.com/~pdw/iftop/) or [`nethogs`](https://github.com/raboof/nethogs): network utilization by socket or process

- `ss`: socket statistics

- `dmesg`: boot and system error messages

- `sysctl`: view and configure Linux kernel parameters at run time

- `hdparm`: SATA/ATA disk manipulation/performance

- `lsblk`: list block devices: a tree view of your disks and disk partitions

- `lshw`, `lscpu`, `lspci`, `lsusb`, `dmidecode`: hardware information, including CPU, BIOS, RAID, graphics, devices, etc.

- `lsmod` and `modinfo`: List and show details of kernel modules.

- `fortune`, `ddate`, and `sl`: um, well, it depends on whether you consider steam locomotives and Zippy quotations "useful"


## Contribution
Contributions are very welcome! Please submit a pull request on GitHub.


