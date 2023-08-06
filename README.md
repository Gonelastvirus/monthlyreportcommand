# AIX monthly report commands

## power server
#bash
<p>bash-4.4# hostname </p>
<p>bash-4.4# oslevel -s </p>
<p>bash-4.4# lmscode -c [ displays the platform system firmware ] </p>
<p>bash-4.4# lspv [ The lspv command displays information about the physical volume ]</p>
<p>bash-4.4# lsvg [  To determine a volume group's ]</p>
     bash-4.4# lsvg -p rootvg <br>
     bash-4.4# lsvg -l rootvg<br>
<p>bash-4.4# df -g</p>
<p>
bash-4.4# lsdev -Cc disk<br>
bash-4.4# lsdev -Cc adapter<br>
bash-4.4# lsdev -Cc memory<br>
bash-4.4# lsdev -Cc processor<br>
bash-4.4# lsdev -Cc tape<br>
bash-4.4# lsdev -Cc planar<br>
</p>
capture topas screenshot
<p>bash-4.4# topas </P>

## cluster
bash-4.4# cd /usr/es/sbin/cluster/utilities<br>
bash-4.4# ./clRGinfo
## vios (padmin)
$ set -o emacs [tells the shell to understand Emacs editing commands e.g. backspace key]<br>
$ hostname<br> 
$ ioslevel<br>
$ lsmap -all<br>
$ lsmap -all -net<br>
$ lsmap -all -npiv<br>
$  df -g
<p>
$ lsdev -Cc disk<br>
$ lsdev -Cc adapter<br>
$ lsdev -Cc memory<br>
$ lsdev -Cc processor<br>
$ lsdev -Cc tape<br>
$ lsdev -Cc planar<br>
</p>




