# Cloc
Powershell mscript used to count the number of lines of the gihub
Provide the argument of github url to count
The script takes one argument, which is any URL that git clone will accept. Examples are https://github.com/evalEmpire/perl5i.git (HTTPS) or git@github.com:evalEmpire/perl5i.git (SSH). You can get this URL from any GitHub project page by clicking “Clone or download”.

Example output:

$ cloc-git https://github.com/evalEmpire/perl5i.git
Cloning into 'temp-linecount-repo'...
remote: Counting objects: 200, done.
remote: Compressing objects: 100% (182/182), done.
remote: Total 200 (delta 13), reused 158 (delta 9), pack-reused 0
Receiving objects: 100% (200/200), 296.52 KiB | 110.00 KiB/s, done.
Resolving deltas: 100% (13/13), done.
Checking connectivity... done.
('temp-linecount-repo' will be deleted automatically)


     171 text files.
     166 unique files.                                          
      17 files ignored.

http://cloc.sourceforge.net v 1.62  T=1.13 s (134.1 files/s, 9764.6 lines/s)
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Perl                           149           2795           1425           6382
JSON                             1              0              0            270
YAML                             2              0              0            198
-------------------------------------------------------------------------------
SUM:                           152           2795           1425           6850
-------------------------------------------------------------------------------
