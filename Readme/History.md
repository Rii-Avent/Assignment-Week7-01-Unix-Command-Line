rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI$ mkdir Assignment-Week7-Unix-Command-Line
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI$ cdAssignment-Week7-Unix-Command-Line\
>
cdAssignment-Week7-Unix-Command-Line: command not found
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI$ cdAssignment-Week7-Unix-Command-Line
cdAssignment-Week7-Unix-Command-Line: command not found
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI$ cd Assignment-Week7-Unix-Command-Line
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line$ git init
Initialized empty Git repository in /mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/.git/
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line$ mkdir Rizki-Ihsan-Qilabi
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line$ cd Rizki-Ihsan-Qilabi
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi$ mkdir sekolah
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi$ mkdir kerja
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi$ cd sekolah
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi/sekolah$ nano ijazah.txt
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi/sekolah$ cat ijazah.txt
Perkenalkan namaku adalah Rizki Ihsan Qilabi
Aku berasal dari Sukabumi
Salam kenal! :D
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi/sekolah$ nano portfolio.txt
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi/sekolah$ cd ..
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi$ cd kerja
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi/kerja$ nano cv.txt
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi/kerja$ cat cv.txt
Assalamu'alaikum.

Perkenalkan namaku Rizki Ihsan Qilabi, saya memiliki kegemaran:
- Memancing Sport
- Menulis/mengetik
- Main Game

rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi/kerja$ cd ..
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi$ cd sekolah
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi/sekolah$ mv portfolio.txt /mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi/kerja
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi/sekolah$ ls
ijazah.txt
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi/sekolah$ cd
rizkiihsanqilabi@DESKTOP-5DDS1VM:~$ cd ..
rizkiihsanqilabi@DESKTOP-5DDS1VM:/home$ cd /mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi/sekolah
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi/sekolah$ cd ..
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi$ cd kerja
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi/kerja$ ls
cv.txt  portfolio.txt
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi/kerja$  git add .
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi/kerja$ git commit -m "Selesai"
[master (root-commit) a397031] Selesai
 2 files changed, 11 insertions(+)
 create mode 100644 Rizki-Ihsan-Qilabi/kerja/cv.txt
 create mode 100644 Rizki-Ihsan-Qilabi/kerja/portfolio.txt
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi/kerja$ ls
cv.txt  portfolio.txt
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi/kerja$ nano portfolio.txt
rizkiihsanqilabi@DESKTOP-5DDS1VM:/mnt/c/Users/PCMANPASI/Assignment-Week7-Unix-Command-Line/Rizki-Ihsan-Qilabi/kerja$































































































