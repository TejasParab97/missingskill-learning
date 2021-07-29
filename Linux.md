#  Linux

### **(1) HISTORY OF UNIX**

 * In 1970 , **BellLab** started resrearch on computers. During 1 years of research they created system known as **UNIX**.but , they are very costly.
 * In 1980 , One of the researcher **Richard Stallman** from _MIT UNIVERSITY_ started his research on free software.
 * In 1985 , **Richard Stallman** started Non-Profit Organization names as, **FSR(_Free Software Foundation_)**.

 >Without Free Software Foundation we are unable to learn about different new technologies. That's why **Richard Stallman** known as _Father_ of free software technology.

 ___
 
 ### **(2) INTRODUCTION TO LINUX**

 * In 1990, Finnish (Finland) Scientist named as , **Linus torvalds** doing some research on Maths & Physics , during research He introduced new Kernel known as **Linux**.
 >Kernel is nothing but, core of operating system. 
 * Linux is completely free as well as GNU is free beacause of that, many developers and researchers started to contribute different packages of GNU project.
 * _GNU_ & _LINUX_ came together and they developed **GNU/Linux** O.S. this is the first Operating system on Linux Kernel.

 [Linux History Picture](https://gitlab.com/TejasParab97/missingskillgrind_tejasparab/-/blob/master/Images%20and%20Screenshots/Linux%20History.jpg)


 ---
 
 ### **(3) ADVANTAGES OF LINUX**
 
 1. **Free Software Licensing**

    * Linux kernel is open source and free so users can use Linux completely free without paying any money.
    * Because of free licensing, Linux os is mostly used in commercial places such as, Schools, I.T. Companies, etc.


2. **Open Source**
   * Linux Kernel(code) is available for everyone. So, programmers can add his own features or modify applications by modifying the source code.
   * Linux is open source that's why many developers stared their own operating system based on Linux
   In  **2020**, almost 99% of technologies working on Linux kernel. currently , there are around **4000** Linux distribtions are avilable in market.
   
   >Distributions are nothing but, Operating Systems.
   
       some of the popular Linux Distributions:-
       
       - Debian
         * Ubuntu
           ~ Linux Mint
         * Kali
         * MX Linux
       - Redhat
         * Fedora
         * CentOS
       - Arch Linux
       - android

3. **Lag free & More Secure**

   * compared to windows operating system, Linux is most lightweight & comfortable for users. You can perform your tasks very smoothly.  
   * Linux is more secure than windows beacuase we can install applications just by passing the command
   e.g.-

       ```
       $ sudo apt insatll package
       ```
       insted of downloading .exe file and then install it in windows.and sometimes .exe file comes with malware or virus. so we can easily insatll application on linux without harm our system.

---

### **(4) LINUX BASIC COMMANDS**

| Command  |  Satnds For |  Function                       |
| :-------:  | :-----------: | ------------------:                         |
|   ls       |   List          |  list all the files and dirctories inside the current working directory.                               |
|  pwd        |  Print Working Directory            |                Prints current working directorie's complete path on your screen.                |
|  cd        |    Change Directory         |    Move from one directory to another directory 
|    cp        |   Copy             |Copy folder or file from one directory to another directory.
|    mv          | Move                   | Move folder or file from one location to another (just like cut & paste in windows)
|     touch           |   -                     |Create an empty file
|   cat             | Concatenate                      |edit the file content / read the file content.
|     mkdir              |    Make Directory                             | Create new Empty Directory.
|    rm / rmdir                    |  Remove / Remove Directory          |Removes file or Directory.
|    ifconfig              |         Interface Configuration                   |Retrieves IP Address Information.
|    ping                  |        Packet Internet Groper                 | Check the Internet Availiability and Internet Speed.
|man                  | Manual                     | Gives all information about commands and flags available for specific command.
|ps             | Process Status                 |Lists all the Applications which are currently running in system.
|which               |       -             | To Identify the location or path of Executable Files/Application's files.
|ssh             |Secure Shell               |Creates Secure Remote Connection between Local system and Server.
|    history         |    -         |Lists all the commands which is previously used by user.
|    clear          |    -            |clears all existing commands from terminal window.
|who|-|Lists all the users Logged in into the system.
|whoami|-|Retrieve only one user who is currently working(Logged in)on the system.
|exit|-|Exit the Terminal.

---


### **(5) LINUX COMMANDS & THEIR FLAGS WITH EXAMPLE**


   * ### ls command & flags
     * #### **ls-a**

       Here, a stands for All Files so, this command lists all files and directories excluding hidden directories & Files too.

       [ls-a example](https://gitlab.com/TejasParab97/missingskillgrind_tejasparab/-/blob/master/Images%20and%20Screenshots/linux%20commands/ls%20commands%20&%20flags/ls_a.png)


     * #### **ls-h**

        Here, h stands for Human so, this command lists all files and directories information in human readable format.

        [ls-h example](https://gitlab.com/TejasParab97/missingskillgrind_tejasparab/-/blob/master/Images%20and%20Screenshots/linux%20commands/ls%20commands%20&%20flags/ls_lh.png)

     * #### **ls-t**

        Here, t stands for Time so, this command lists all files and directories sorted by Timestamp.(newly created files came on top.)

        [ls-t example](https://gitlab.com/TejasParab97/missingskillgrind_tejasparab/-/blob/master/Images%20and%20Screenshots/linux%20commands/ls%20commands%20&%20flags/ls_lt.png)

     
     * #### **ls-r**

        Here, r stands for Reverse so, this command lists all files and directories in reverse order.

        [ls-r example](https://gitlab.com/TejasParab97/missingskillgrind_tejasparab/-/blob/master/Images%20and%20Screenshots/linux%20commands/ls%20commands%20&%20flags/ls_lr.png)

   * ### cd command & flags
      * #### **cd..**

        Here, .. stands for one directory back, this command takes you to the one folder back.

        [cd.. example](https://gitlab.com/TejasParab97/missingskillgrind_tejasparab/-/blob/master/Images%20and%20Screenshots/linux%20commands/cd%20commands/cd%20back%20one%20directory.png)

     * #### **cd_**

        Here, _ stands for Previous back, this command takes you to the Previous directory.

        [cd_ example](https://gitlab.com/TejasParab97/missingskillgrind_tejasparab/-/blob/master/Images%20and%20Screenshots/linux%20commands/cd%20commands/cd%20previous%20directory.png)

* ### Mkdir command & flags
    * #### **mkdir <dir_name /subd_name> -p**
       
        Here, Using this command we can create directory with multiple sub-directories inside it.

        [mkdir <dir_name /subd_name> -p example](https://gitlab.com/TejasParab97/missingskillgrind_tejasparab/-/blob/master/Images%20and%20Screenshots/linux%20commands/mkdir%20commands/mkdir_directory%20with%20subdirectory.png)

* ### rm / rmdir command & flags
    * #### **rm-rf**

        Here, r stands for Recursive & f stands for Force.
        using this command, we can delete folders which has consists of of files and sub-directories in it.
        >rmdir command only delete empty directories.
        if you add * after rm then it delete all the files and folders from current directory.

        [rm-rf example](https://gitlab.com/TejasParab97/missingskillgrind_tejasparab/-/blob/master/Images%20and%20Screenshots/linux%20commands/rm%20%20or%20rmdir%20commands/rm%20all%20f&f.png)

* ### mv command & flags
    * #### **mv (source-value) (new-value) file-name**

        We can use this commad to rename the file.first select desired file and then provide suitable name for the file.

        [mv as rename example](https://gitlab.com/TejasParab97/missingskillgrind_tejasparab/-/blob/master/Images%20and%20Screenshots/linux%20commands/mv%20commands/mv_as%20rename.png)


---

### **(6) LINUX FILE STRUCTURE**
  
   *  In Linux based Operating systems, **Every program, commands and  Executable Files** considered as **File*
   * In Linux Every file comes under the **ROOT** Folder.
   Linux follows hierarchical file structure.
   * so, **Root** folder are works like root of trees. and user folders are branches of Root folder.
   * if you want to enter in your system's root directory, then use following command:-
   
   ```
   cd/
   ```
   * / denotes ROOT DIRECTORY
     
     ~ denotes USER DIRECTORY

   
   * If you are in user's directory then, you will see (**$**) sign in your terminal but,
   If you are in root directory then, you will see (**#**)sign in your terminal.


     
   * **tail-100f** command is used for achieve log of all files in system.
   here , _100_ stands for last 100 lines.


   [Linux File Structure Image](https://gitlab.com/TejasParab97/missingskillgrind_tejasparab/-/blob/master/Images%20and%20Screenshots/Linux%20file%20structure.jpg)

   ---

   ### **Root Directory Folders**

   | Folder Name  | Description     |
   |:-------------: | :-----------------:|
   |      /bin        |  user's binary files are stored here (**Commands & Application files**)            |
   | /boot | System's Kernel & boot files stored here |
   |/sbin |system binary files are stored(**Root user/System's Admin**) |
   |/dev | External Devices like PenDrive,Mouse,etc. are mounted |
   | /home|All Users as well as their data stored here |
   |/usr |User's system directory, User related resources stored here |
   | /root| Root user's data stored here|
   | /var|System level Variable (**Log & Configuration Files**)stored here |
   |/sys | Device informations are stored and modified
   | /tmp| Temporary files are stored here|
   | /etc|System software's configuration and binary files are stored here
   |/lib | shared system's libraries are stored here|
   | /proc|show current system's information |
   |/opt |Third party software's files are stored |

   ---