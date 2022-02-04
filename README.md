# 42Cursus_Born2BeRoot

Here I am resuming all the things I needed on this project.


  VirtualBox - Objetivo é criar ambientes para a utilizaçã de sistemas distintos como se fossem diferentes computadores no mesmo harware. Suporta sistemas como Windows, Linux, MacOs, Solaris etc.
As Virtual machines correm no sistema Hipervisor. O computador onde corre o sistema é o host e as máquinas virtuais são guests. A VirtualBox usa o Hipervisor de tipo 2 ou hosted e funciona como descrito na imagem :

![382px-Hipervisor_-_Segundo_nivel svg](https://user-images.githubusercontent.com/56501818/152022870-dc39c6cf-2ac9-401e-b7c5-4d6c2852bea0.png)

  Debian - É um sistema operacional de software livre mantido por crowdfunding e opensource. Uma das melhores features é o APT(Advanced Package Tools) que permite a fácil instalação e desinstalação em sistemas género unix. Ubuntu is based on Debian arquitechture.

  CentOS - Community Operating System é uma distribuição Linux e é basicamente uma cópia grátis do sistema operativo Red Hat Enterprise Linux
 
Debian and CentOS are the main used Linux distributions in the market and are both free. O CentOS é mais estável e normalmente não tem grandes mudanças durante cerca de 7 anos. O Debian costuma mudar com maior frequência, geralmente 2 anos. A comunidade do Debian é muito maior. CentOS é mais complicado de aprender para um beginner. CentOS é muito mais estável e por isso é que também demoram mais a desenvolver e lançar. Debian é mais seguro porque atualiza mais vezes. Em termos de software packages o Debian é melhor: CentOS está mais focado no meio empresarial enquanto o Debian tem cerca de 60 mil packages grátis. 
   
  KDump - is a linux feature que guarda a memória do programa quando o computador crasha ou desliga abrutamente e permite anlisys for debugging and determining the cause of crash. Quando acontece um erro destes o KDump inicia um novo kernel with the data and memory saved. All the memory RAM(Random Access Memory) is preserved and saved so it cannot be overwritten due to the crash handle 
  
  SELinux - Security-Enhanced Linux is an implmentation of the MAC(Mandatory Access Control) arquicthure in Linux. It was developed by NSA and it works as a security server. It provides a variety of security policies. Running SELinux under a Linux distribution requires three things: An SELinux enabled kernel, SELinux Userspace tools and libraries, and SELinux Policies (mostly based on the Reference Policy). Some common Linux programs will also need to be patched/compiled with SELinux features.
  
  AppArmor - is a Mandatory Access Control (MAC) system, implemented upon the Linux Security Modules (LSM). It is an alternative to SELinux and easier to install and adapt to the system. It controls the permissions of users to take actions and triggers messages to the system when somone trys to hack. it takes a matter of ours to hack AppArmor. AppArmor supplements the traditional Unix discretionary access control (DAC) model by providing mandatory access control (MAC)
  
  LVM - Logical Volume Manager
  LVM is used for the following purposes:
    Creating single logical volumes of multiple physical volumes or entire hard disks, allowing for dynamic volume resizing.
    Managing large hard disk farms by allowing disks to be added and replaced without downtime or service disruption, in combination with hot swapping.
    On small systems (like a desktop), instead of having to estimate at installation time how big a partition might need to be, LVM allows filesystems to be easily resized as needed.
    Performing consistent backups by taking snapshots of the logical volumes.
    Encrypting multiple physical partitions with one password.

LVM can be considered as a thin software layer on top of the hard disks and partitions, which creates an abstraction of continuity and ease-of-use for managing hard drive replacement, repartitioning and backup.
  
  Ncurses - is a programming library providing an API, allowing the programmer to write text-based user interfaces, Text User Interface (TUI), in a terminal-independent manner. It also optimizes screen changes, in order to reduce the latency experienced when using remote Unix shell.
  
  Aptitude - is an Ncurses and command-line based front-end to numerous Apt libraries, which are also used by Apt, the default Debian package manager. Aptitude is text based and run from a terminal.
  Aptitude has a number of useful features, including:
    a mutt-like syntax for matching packages in a flexible manner
    mark packages as "automatically installed" or "manually installed" so that packages can be auto-removed when no longer required (feature available in Apt,    too,   since quite a few Debian release)
    preview of actions about to be taken with different colors marking different actions
    the ability to interactively retrieve and display the Debian changelog of all available official packages
apt-like (i.e. apt-get and apt-cache) command line mode ("aptitude install foo")
    Score-based dependency resolver which is more suitable for interactive dependency resolution with additional hints from the user like "I don't want that part of the solution but keep that other part of the solution for your next try". Apt's dependency resolver on the other hand is optimized for good "one shot" solutions.  
    The primary command is "aptitude"
  
  Apt - Advanced Package Tool
    The main command-line package manager for Debian and its derivatives. It provides command-line tools for searching, managing and querying information about packages, as well as low-level access to all features provided by the libapt-pkg and libapt-inst libraries which higher-level package managers can depend upon.
  
  SSH - Secure Shell
    Secure Shell (SSH) is a cryptographic network protocol for operating network services securely over an unsecured network. Typical applications include remote command-line login and remote command execution, but any network service can be secured with SSH. GIT is an example of uing SSH.
    A criptografia usada pelo SSH objetiva fornecer confidencialidade e integridade de dados sobre uma rede insegura, como a Internet, apesar dos arquivos vazados por Edward Snowden indicarem que a Agência de Segurança Nacional pode algumas vezes descriptografar o SSH, permitindo-os ler o conteúdo de sessões SSH
  
  UFW - Uncomplicated Firewall is a program for managing a netfilter firewall.
  
  Firewall - Is a sotware or hardware used in a computer network which applies a security policie determining the security level and the data that is allowed to go in and out the network. It creates a safety barrier between a private network and the internet
  
  ![2B7BC106-349A-43EF-AFBD-D7EA2E79490E_1_105_c](https://user-images.githubusercontent.com/56501818/152540984-fd36ae4f-04f7-48ef-bfd9-8afd7b0ed25f.jpeg)

  
  DNF
  sudo
  TTY mode password
  IPv4
