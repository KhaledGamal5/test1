khaled@pop-os:~$ pwd
/home/khaled
khaled@pop-os:~$ ./system_info.sh
bash: ./system_info.sh: Permission denied
khaled@pop-os:~$ chmod +x system_info.sh
khaled@pop-os:~$ chmod +x file_check.sh
khaled@pop-os:~$ chmod +x rename_files.sh
khaled@pop-os:~$ chmod +x calculator.sh
khaled@pop-os:~$ ls -l
total 68
-rwxrwxr-x 1 khaled khaled 1462 أغس 24 00:51  calculator.sh
drwxrwxr-x 7 khaled khaled 4096 أغس 14 19:19  desktop
-rwxrwxr-x 1 khaled khaled  224 أغس 24 00:49  file_check.sh
drwxrwxr-x 2 khaled khaled 4096 أغس  8 21:25  gamal@
drwxrwxr-x 2 khaled khaled 4096 أغس  8 21:25  @khaled
drwxrwxr-x 4 khaled khaled 4096 أغس  8 22:00 'khaledd gamal'
drwxrwxr-x 2 khaled khaled 4096 أغس 19 19:54 'khaled gamal'
-rwxrwxr-x 1 khaled khaled  192 أغس 24 00:50  rename_files.sh
-rwxrwxr-x 1 khaled khaled   77 أغس 24 00:45  system_info.sh
drwxr-xr-x 4 khaled khaled 4096 أغس 14 11:03  التنزيلات
drwxr-xr-x 2 khaled khaled 4096 أغس 24 00:35 'سطح المكتب'
drwxr-xr-x 2 khaled khaled 4096 أغس  8 05:16  صور
drwxr-xr-x 2 khaled khaled 4096 أغس  8 05:16  عام
drwxr-xr-x 2 khaled khaled 4096 أغس  8 05:16  فيديو
drwxr-xr-x 2 khaled khaled 4096 أغس  8 05:16  قوالب
drwxr-xr-x 2 khaled khaled 4096 أغس  8 05:16  مستندات
drwxr-xr-x 2 khaled khaled 4096 أغس  8 05:16  موسيقى
khaled@pop-os:~$ ls -1
calculator.sh
desktop
file_check.sh
gamal@
@khaled
'khaledd gamal'
'khaled gamal'
rename_files.sh
system_info.sh
التنزيلات
'سطح المكتب'
صور
عام
فيديو
قوالب
مستندات
موسيقى
khaled@pop-os:~$ ./system_info.sh
Username: khaled
Kernel Version: 6.2.6-76060206-generic
khaled@pop-os:~$ ./file_check.sh file1.txt /home/khaled/Documents
File does nor exist
khaled@pop-os:~$ ./file_check.sh file1.txt /home/khaled
File does nor exist
khaled@pop-os:~$ ./file_check.sh $1  /home/khaled
File exists
Contents of /home/khaled:
cat: //home/khaled: Is a directory
khaled@pop-os:~$ ls
 calculator.sh   file_check.sh   @khaled         'khaled gamal'     system_info.sh  'سطح المكتب'   عام     قوالب     موسيقى
 desktop         gamal@         'khaledd gamal'   rename_files.sh   التنزيلات        صور           فيديو   مستندات
khaled@pop-os:~$ touch filex.txt
khaled@pop-os:~$ ls
 calculator.sh   file_check.sh   gamal@   'khaledd gamal'   rename_files.sh   التنزيلات     صور   فيديو   مستندات
 desktop         filex.txt       @khaled  'khaled gamal'    system_info.sh   'سطح المكتب'   عام   قوالب   موسيقى
khaled@pop-os:~$ ./rename_files.sh txt
khaled@pop-os:~$ ls
 calculator.sh   file_check.sh   @khaled         'khaled gamal'   rename_files.sh   التنزيلات     صور   فيديو   مستندات
 desktop         gamal@         'khaledd gamal'   new_filename    system_info.sh   'سطح المكتب'   عام   قوالب   موسيقى
khaled@pop-os:~$  ./calculator.sh
1. Addition
2. Subtraction
3. Multiplication
4. Division
5. Exit
Enter your choice:  3
Enter the first number:  4
Enter the second number: 5
4 * 5 = 20
1. Addition
2. Subtraction
3. Multiplication
4. Division
5. Exit
Enter your choice:  5
Exiting...
khaled@pop-os:~$ 


