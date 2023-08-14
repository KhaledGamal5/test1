khaled@pop-os:~$ cd التنزيلات
khaled@pop-os:~/التنزيلات$ unzip Updated-Task-02.zip
Archive:  Updated-Task-02.zip
   creating: Updated-Task-02/
  inflating: Updated-Task-02/README.txt  
  inflating: Updated-Task-02/.level-1.tar  
khaled@pop-os:~/التنزيلات$ tar xvf Updated-Task-02/.level-1.tar
.level-1/
.level-1/README.txt
.level-1/level-2
khaled@pop-os:~/التنزيلات$ cd level-1
bash: cd: level-1: No such file or directory
khaled@pop-os:~/التنزيلات$ cd .level-1
khaled@pop-os:~/التنزيلات/.level-1$ ls
level-2  README.txt
khaled@pop-os:~/التنزيلات/.level-1$ cat README.txt
Decompress "level-2".
Hint: Most compression tools require it's suffix.
khaled@pop-os:~/التنزيلات/.level-1$ ls
level-2  README.txt
khaled@pop-os:~/التنزيلات/.level-1$ file level-2
level-2: gzip compressed data, was "level-2.tar", last modified: Wed Aug  9 17:59:07 2023, from Unix, original size modulo 2^32 112640
khaled@pop-os:~/التنزيلات/.level-1$ tar -xf level-2
khaled@pop-os:~/التنزيلات/.level-1$ gunzip level-2.gz
gzip: level-2.gz: No such file or directory
khaled@pop-os:~/التنزيلات/.level-1$ cd level-2
khaled@pop-os:~/التنزيلات/.level-1/level-2$ ls
01VzXCtEZS  AVR4cOJJui  F7HxYNlWa1  kuDj7Ti4Id  pRQVevx1kv  vm5P2xLF3s
09tuxAUkSZ  AXkzOy8ZzP  feBbPjPHsA  kVQzoTdmBO  PVhcqo825N  VMVoKBX4Qu
0MaqBh51eE  b8L3KxPJL3  FKtcWd8ViA  L3QwW94Azo  Q6QURkVvYf  vOcM3EYMXw
1Rc48mLISP  bc83b2Byu2  fky7p46DOi  l6FQ8rGXcW  QIGyaTtmlW  VUOJouKqL9
1t7LeNZeIl  BeSbKu0Ogb  fSikeo7Jtz  l8fShvYkRA  QirM8dLKSD  VxWCuMyoCO
2dBiyDY1PQ  BsdD4ojJkc  fTBdzWqgkc  lcVizkoO1R  Qv3QTzvZC1  w9ophYtx44
2tqNyIRWZk  bvSabnQtuB  FUSxQX2TeD  lvEy6vrtZe  README.txt  waa5BUbYjL
3aI6ZRWi7g  ciyaIBrj64  g18DV62wEd  LXdwN4DGye  rHC2JXoQSc  wfbzcLn49x
3HClX3dFMm  clktsGviqW  gB9k1O4ZT6  lxQpP8fJrM  rjS1PORSqI  WU2NIZw5bL
3nhuQzOgpI  CoXO2qfhv8  gBT5u0vLT5  mIQgRJXCLp  rn4s52kOCO  WWgF2QTu1U
40Mg6vDbYN  cqxENw21F1  Gf0hDzawoe  mLD2604WjZ  rnTFX18Jh9  WxGYCzojb5
4bq72IzcAj  cTJdoZGT00  Gi0sWVVQmE  mMwQyrbtaZ  rTAkta2aW2  WzkBDyZf09
4CkUBprXze  cUJtGyfwcE  GqeOr84K6i  Mn1k5s3x2R  rzz4HDYtQb  x2OxGPBNwZ
4OAvfgFenY  cuL74htcTP  gUm1Kw3MsJ  mTJFxGhibA  s82TBxnZgd  X7by8vw474
4Qm9FLdd1E  cYLRnO8xIB  GuxvN3cJ7U  n80qgsvhlQ  SkWLO4DmJj  xiRKbhzAt6
4TqWZorrCe  D240Im7S6f  H2TS1vp6Xt  n8QxXKvUat  soPx5vMfvS  Xnmws6DuHJ
54is18fJ6D  dcWFp0gN0U  HC3gnSrNHL  n9Gy45gDYd  SpGacqvoQe  Y2WinDQzOb
5CnJF4NcXe  dkbSpLYJE5  HDe7NHRINO  NABe6RrZS9  Sv7z35zbDG  y7U81AE7BP
6jKgIUUWGx  DQ3kjLgCUV  HRHgAeIQKP  NB8PtjcBPu  T4TiKdPbRw  yc0GFVKDtL
6LythIyWzQ  dW436qn2Pa  hsM9mQuMTH  NuvecJk6rH  tmDRcrdYa9  YH3RBGocdA
6QcByCct9B  DWahK49MnT  hynub0MKNl  nV9Fht2ABW  TynxkdcmfZ  ymuoaRLefH
7B5l8AC1M8  dwmlaLoghH  Ib1jBtgkP4  O0Jt20BDT8  u8APo7fuFv  yWegzIJdDb
7dnQ0OZO7U  DYCdqY7wJN  iJfohlDIrt  o1hEPIsnq0  uCBBCPnmb2  yWY8iLmL2v
7f6nrbSyXM  E0bi5j8X9V  IXzIL2c9IA  o5zluFzkcg  uH7zN1UJSF  Yx2PUbl2gA
8HuZDGUf7D  EC1LKYOR0Z  jbZwCGWF1u  oATDmz0CAK  UkoXWlT8ck  ZDe6elrEn5
8lNsncDmgT  ECIShbzsBE  jGu9MApzJB  OBfROJ7kKU  UkXg7Lp9iV  ZgiaL4uwSD
a8wKwwWNRJ  EDPOSQuyWk  JiMEslX4PO  OEQ9RG7Cam  Uo2uLQHfWm  ZhfPkBCn6B
ABtpOP8TR9  EJd4UALueA  JVucZ5s2sO  OlDXrxU8tn  URJcbPH7ig  zQ85ieoBzD
AbyVd8kDq7  emEeo94yqd  jzjKDCAuJh  OQUNDxbuAf  uUeLfbjNyx  zTpHflQtBt
aD09T4P1xb  eRz0wDJzB6  k0KGHDEFmp  P9w2t9K9Ju  UUrQyToe6M  ZwCSnEFDCS
afHUHOaYAb  Etsj7NECd9  KNXMn8sBL8  PBQjGeeXZ2  uYt23HMkvu  zXOU7yVyjx
AKf6S1hWVZ  eTY7qTsykD  KO4TANambB  PDsc45eDhU  v2LInrvkDO
AofrZBGKhB  evJEy0ce9D  kPIkdmGR9B  po63smRLBt  v9kNm4bENt
aT6OddrPAr  f4sJ94QCRL  kr6RDEYCed  pptcUXKeGS  VkL2bz9W98
khaled@pop-os:~/التنزيلات/.level-1/level-2$ find -type f -name "*txt"
./README.txt
./README.txt
bash: ./README.txt: Permission denied
khaled@pop-os:~/التنزيلات/.level-1/level-2$ cat ./README.txt
Locate "level-3".
Locate "level-3".
Use a general method to decompress it.
Command 'Locate' not found, did you mean:
  command 'locate' from deb plocate (1.1.15-1ubuntu2)
Try: sudo apt install <deb name>
khaled@pop-os:~/التنزيلات/.level-1/level-2$ find -name "level-3"
./gBT5u0vLT5/level-3
./gBT5u0vLT5/level-3
bash: ./gBT5u0vLT5/level-3: Permission denied
khaled@pop-os:~/التنزيلات/.level-1/level-2$ unzip ./gBT5u0vLT5/level-3
Archive:  ./gBT5u0vLT5/level-3
  End-of-central-directory signature not found.  Either this file is not
  a zipfile, or it constitutes one disk of a multi-part archive.  In the
  latter case the central directory and zipfile comment will be found on
  the last disk(s) of this archive.
unzip:  cannot find zipfile directory in one of ./gBT5u0vLT5/level-3 or
        ./gBT5u0vLT5/level-3.zip, and cannot find ./gBT5u0vLT5/level-3.ZIP, period.
khaled@pop-os:~/التنزيلات/.level-1/level-2$ tar -xf ./gBT5u0vLT5/level-3
khaled@pop-os:~/التنزيلات/.level-1/level-2$ gunzip ./gBT5u0vLT5/level-3
gzip: ./gBT5u0vLT5/level-3: unknown suffix -- ignored
khaled@pop-os:~/التنزيلات/.level-1/level-2$ gunzip ./gBT5u0vLT5/level-3.gz
gzip: ./gBT5u0vLT5/level-3.gz: No such file or directory
khaled@pop-os:~/التنزيلات/.level-1/level-2$ cd ./gBT5u0vLT5
khaled@pop-os:~/التنزيلات/.level-1/level-2/gBT5u0vLT5$ ls
level-3
khaled@pop-os:~/التنزيلات/.level-1/level-2/gBT5u0vLT5$ tar -xf level-3
khaled@pop-os:~/التنزيلات/.level-1/level-2/gBT5u0vLT5$ gunzip level-3.gz
gzip: level-3.gz: No such file or directory
khaled@pop-os:~/التنزيلات/.level-1/level-2/gBT5u0vLT5$ cd level-3
khaled@pop-os:~/التنزيلات/.level-1/level-2/gBT5u0vLT5/level-3$ find -type f -name "*.txt"
./README.txt
khaled@pop-os:~/التنزيلات/.level-1/level-2/gBT5u0vLT5/level-3$ cat ./README.txt
You're seeking a file with a certain size.
Find the link to get the size.

khaled@pop-os:~/التنزيلات/.level-1/level-2/gBT5u0vLT5/level-3$ ls -li
total 804
678888 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 00aBxtql7r
679061 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 0aba2tPi4R
679075 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 0QYBUNJixX
679140 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 17pfO4tY4m
678852 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 1NBA3mJTQC
678895 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 1pnvifRmA6
679035 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 22ix6enm8X
678835 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 2GsF4Kn1PG
679119 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 2IFaRh0Jxc
679130 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 30msooUqJf
678762 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 3Ig28f7Xa8
679064 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 3SSDrwrwmt
679029 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 3TpnDd6PaY
679129 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 3wTdqmDig6
678849 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 3XXNloi4gV
679143 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 3YhvETOVcv
679089 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 4jFmUBgygR
678816 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 4vG2fYLy6B
678847 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 53IaK7n1np
679137 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 5H5OLdA8qE
678827 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 5ME7YKcHsa
679055 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 5tAchjHlmE
678839 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 5tJnO1Mwzf
679133 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 5VoPA03kvi
678836 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 6AJpxbHYkm
679053 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 6C8RwQ9kGP
679112 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 6hnWZbro0I
679039 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 6JPHCI1K8M
679032 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 6lie6mPCRe
678821 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 6mnK6keHIi
678875 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 6mpTfHgnlX
679084 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 6vigp6VM7d
678795 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 6ZJgIXN3P0
679077 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 71qxiSKgAY
679065 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 74gKRNrKVf
678826 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 77RwxhcZTx
678877 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 7C4OyiuQc4
679118 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 7nMGZvigiL
678331 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 7PFGHcmfa2
678813 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 7sxFwD2jGw
678760 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 82aRYKaCZB
679083 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 88exEg2MMo
678769 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 8IOqsSAWIo
679076 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 8OLXyd5ai0
679050 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 8u4f62oAYb
678831 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 8X1ovlX6ex
678754 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 9CA6eRBprt
678868 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 9GqYmpQsAS
679141 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 9my7brVWmo
678838 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 9NNnGuH7A1
678837 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 9QBLcfEf91
678851 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 a6HPyy5Mz5
679139 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 A8SqBitLRB
678867 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 aFjSvqXqWE
679145 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 AI8sfDgnhT
679070 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 AJtW9NcRLy
679030 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 ANRcGwDkvK
679148 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 ayHSb1kjNd
679120 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 b4BF572o41
679102 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 b957oPA24t
678874 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 Bb0kZiNxDz
678815 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 BbreWoCXSv
678858 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 bduLsR7v4K
678902 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 bOKXTvk63r
679068 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 BrJvEu79eg
678889 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 BTf86zJsB3
679100 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 byVoAmiOqs
679037 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 bze36b6xjZ
678810 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 C5KrlOGYlu
679031 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 cDfzzIGULi
678808 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 cF1AG2dtLr
679147 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 cjcKUQDGLl
678757 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 cKiyNtE0yD
678748 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 ClbTpohwVU
678825 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 cStCLsSELl
678822 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 ctnOoPIga1
678750 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 cWRi45wacA
679058 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 cWZv9iI87X
678892 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 cX6YaqFDFY
679046 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 D5JYr3I592
679094 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 dBJSXzmpb1
678869 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 Dd9KxIjxSB
678906 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 dK320XCmR0
678864 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 DKiaUm3WBb
678767 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 Doi1I9Z8TE
679056 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 dqbKkDKbZl
678792 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 dtLZdglPV3
679045 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 Dux6sHDdCW
678863 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 EHm7bcCxj1
679099 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 epBL6naqQR
679074 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 ePj0HMi3nh
678765 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 Eqk382soFH
678883 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 eT21MMr22o
679042 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 eT909HWyck
678780 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 ETRyNzIpYk
678761 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 ev8BCScTMa
679026 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 F5Db7l8s9j
678824 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 F9OYJjkGiB
678904 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 fCLOGDR05y
678855 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 Fdvgo1aqTT
678794 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 FeBBLsJEYS
678809 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 FJsgrBEwbJ
678774 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 flbjrqIXMS
679125 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 fn95Z2sG3o
678854 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 FYrh0rmC4q
678785 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 G9UhKYNLgv
678908 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 GaMed1WIDN
679066 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 gcb0bfLbVM
678751 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 gfLQDXjJAW
679144 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 Gksn5ca8Jn
679150 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 gOWuBZZgn2
679073 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 GPaN65ikSl
678802 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 gu78Zpnknw
679135 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 gu92R3c92I
679023 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 gupiPOsJzC
679024 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 hb4zKjD5G4
678783 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 hBv1LejGKu
678828 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 Hf8ovJhWKI
678800 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 hGCeu2NgZ5
678896 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 HuSBc8QKYi
679090 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 HXq7gqQZ5Z
678747 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 i4CkeVfT7S
679051 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 iCR4qC97HM
678884 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 IE4xWwbydi
679085 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 IiLRIuK1Fi
678853 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 IKeqpTmvmW
679096 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 ioOe8b7TsJ
679072 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 iOplykVsBo
678907 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 ip23ESdwGT
678829 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 IygdcTaoYP
678806 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 iymCtoFUVf
678777 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 j3JsNAEsm1
679136 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 J3K5BY52dp
679126 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 J5feTUwPso
679057 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 jahdjqT54b
678905 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 JArjmQWPVq
678873 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 JBDnoFKLcx
678857 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 JbMcWq9tku
678799 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 Jc0EEC4sua
678772 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 JgVwSWAUsr
679022 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 JlhNaDm4f7
679033 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 JnOT2WHKbE
678833 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 jpO4wGMT57
679106 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 JqAekDHYif
678811 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 jrMKucOmtp
679062 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 jVBkVAbTHj
678755 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 jVGv0HeZvG
678778 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 jvyPQ8Z8ht
679034 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 JYdPDFpOIe
678798 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 k2yYJNQcLu
678812 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 K56S3V4AQ6
679040 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 K9kyHBbw7y
678842 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 Kfce3CFjhh
679109 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 KJBdbwTmzD
678791 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 kkIu8kVXLo
679041 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 kOIOppD8hx
678890 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 kp1ujuDGKO
679081 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 krWRFtvYDP
679025 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 kT3eEAfVcY
678779 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 kwmQK5z76U
678782 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 L5DOn3iY18
679038 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 L8ZzpZTLz5
679114 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 LeUtklcfmE
679086 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 LKfMizQQjE
679049 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 lowIuX2RQI
679132 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 LtH4X99Uw3
678756 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 LZ5jebusoa
679091 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 M1vV6QxnH1
678804 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 m59pSiQG2p
678910 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 m7lRDpRTUJ
679067 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 MaqkHpS39h
679117 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 MKQErXMkPE
678770 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 moQuVgMB1f
678753 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 mRET49bBGR
679047 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 mu6c42Y1qo
679105 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 mwILTjPhCP
679082 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 mxG418at98
679123 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 mydABLXwyL
678893 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 n4d9SlSzcV
678881 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 n4MCXv5XM2
678744 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 N5lXyVotHN
679107 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 nBoQgGxoGX
678764 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 NdkrRTZmr9
678856 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 NHag0dTW3U
678775 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 nlgqxKuRC3
678823 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 NLM96g2hH3
679101 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 Nmuh6DvLkc
678844 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 nR711EHtmU
678841 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 nSC9OkT1E3
679121 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 nwt49CVPtC
678903 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 O009zeKkif
678872 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 O0V7mQCicJ
678759 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 o6Q2i1NUXc
678865 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 OAbH1oFg57
679027 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 OaRp7TV8pe
678773 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 ObIefWWqqM
678749 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 OFx3U24MoP
678745 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 OHWTswrtBk
678763 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 ojc7SuLzMV
678899 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 orzpz7CBBQ
678797 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 Ou1q6zOh5n
678861 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 oV3aef60WL
679052 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 OXZ3OOGJ7O
679093 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 oZ5HOQe6X0
678885 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 p194n4sSpi
678866 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 p3ARvi0q4F
678766 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 p6PVEBfSyK
678887 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 PaOzJn0sJV
678848 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 PDJdFxfgvh
678843 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 penDnjNMQc
678898 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 pH9s3o8foP
679028 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 pI49N7Zoxn
678891 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 Pmf5TqkkYg
678850 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 pO4Lt5DPrX
678788 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 psmL4dk69Y
679122 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 pXXxEWcKkz
678771 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 q4gh4nODZa
678819 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 qFO0JDSF0N
678786 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 Qh9GBAd3mF
679116 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 QM053Y9Vw1
678859 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 R0LpA1qK4F
679079 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 R6okint5JZ
678878 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 R82WkcyQAx
678876 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 rcEkx0b0WC
678789 -rw-r--r-- 1 khaled khaled   75 أغس  9 17:35 README.txt
678805 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 rgNTkxVkxN
679048 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 RnL5L0QLbY
679054 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 RPZAvV75tm
679043 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 RU4rJzjPfg
679063 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 RWWLnFwGtv
679097 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 rwZwqdxHhJ
679115 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 rzSTDqa7oV
679059 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 SaaZymLdoG
678793 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 SaQtx8SNld
678817 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 sf7ajd5INC
679021 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 skVRxkHK04
679020 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 sNrtW0eiZF
678781 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 SqAZPx7CbA
678862 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 SRgPbWeEG6
678901 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 sRhTcN4PIw
678818 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 sVyNLUXzut
679036 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 T0gYx5T5ks
679128 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 Tbi1MdwiMX
678879 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 tEgA7tGwxB
678807 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 TezFlyJz9o
679113 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 TFkiwAHDrG
678845 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 Tt0xmDrg4Y
678860 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 tZCE2HQg8s
678894 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 uAw4PKT7E0
679060 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 udqz57oeuX
678803 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 ufdeX2Dk7C
678840 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 v2ME2J4GuF
678871 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 V64A9vKnYq
679151 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 vkaOISlk2I
678790 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 vLWtq7N2aR
679044 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 VneCQhwmfv
679108 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 vUbRKbYlKR
678820 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 Vw5Jm3saUP
678758 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 vz1uLzTKjO
679095 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 VZw2jtUdZD
678776 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 W6AdwbmalK
678784 -rw-r--r-- 1 khaled khaled   34 أغس  9 17:35 WfUKyzFeEv
678814 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 WFyKhZdOcx
678880 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 wgibrPHhJq
679078 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 WhTtCYas3M
679098 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 wJC19bchr2
679146 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 WLuasYnMvP
679092 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 Wm14GdEGcm
679071 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 wpJyCPLODS
678796 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 wpoGQ7WmSg
678870 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 WSxUR7IJd8
678909 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 wZ4LJKpHW6
679080 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 x2CDPgz6Jk
678801 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 x3Nvoy3Ucl
679087 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 x3SkxfEItU
679127 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 X62Vq1yIyL
678768 lrwxrwxrwx 1 khaled khaled   10 أغس  9 17:35 X6lkChFKsj -> WfUKyzFeEv
678832 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 XapfbudtZp
678834 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 xBsGYZHomA
679111 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 xigSiLU79u
678746 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 XkrAGaosYZ
679124 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 xRxKkdCTU8
679104 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 xYCpOSRLsl
678752 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 xYlmccmE5f
678787 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 Y0nB0Ep1my
679142 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 y1IAp2YdZc
679103 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 Ye8R8ZOvJ9
679138 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 ygasPrK3kG
679088 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 YgeyHmPrtP
678897 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 ysdoXYcYQq
679131 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 YVAPjrh8Up
678900 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 zEmK04yIqc
679069 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 ZenzUsQydR
678830 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 zet1AFeHNl
678846 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 zghxQE4JGJ
679149 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 ZNq1fiVP6F
679110 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 zxmnKldpmY
678886 drwxr-xr-x 2 khaled khaled 4096 أغس  9 17:35 zzgiKI2xSS
678882 -rw-r--r-- 1 khaled khaled    0 أغس  9 17:35 zZU6ymQky6
khaled@pop-os:~/التنزيلات/.level-1/level-2/gBT5u0vLT5/level-3$ cd X6lkChFKsj
bash: cd: X6lkChFKsj: Not a directory
khaled@pop-os:~/التنزيلات/.level-1/level-2/gBT5u0vLT5/level-3$ tar -xf WfUKyzFeEv
tar: This does not look like a tar archive
tar: Exiting with failure status due to previous errors
khaled@pop-os:~/التنزيلات/.level-1/level-2/gBT5u0vLT5/level-3$ find -size 10
khaled@pop-os:~/التنزيلات/.level-1/level-2/gBT5u0vLT5/level-3$ cat WfUKyzFeEv
73 bytes is your target file size
khaled@pop-os:~/التنزيلات/.level-1/level-2/gBT5u0vLT5/level-3$ find -size 73c
./m7lRDpRTUJ/xVMvVOKNW5
khaled@pop-os:~/التنزيلات/.level-1/level-2/gBT5u0vLT5/level-3$ cat ./m7lRDpRTUJ/xVMvVOKNW5
Congrats!! You have finished the Task Successfully, you can rest now :D.
khaled@pop-os:~/التنزيلات/.level-1/level-2/gBT5u0vLT5/level-3$ 


