# AIX monthly report commands
# VIO Client Report
## Finacle Application Server (finapp1)
## Finacle Database Server (findb1)
## Finacle Web Server (finweb1)
## Finacle Web Server (finweb2)
## Finacle Application Server – HA (finapp2)
## Finacle Database Server - HA (findb2)
## Finacle DR Application Server (drappserv)
## Finacle DR Database Server (drdbserv)
## Finacle DR Web Server (drwebserv)

# screenshot
## Storage-DC
## Storage-NDR
## Storage-DR
## HMC
     ### HMC VIO-A
     ### HMC VIO-B
## (Integrated virtual Manager) IVM-DR
## Tape-DC
## Tape-DR
## SAN-A
## SAN-B


## power server
#bash
<p>bash-4.4# hostname </p>
<p>bash-4.4# oslevel -s </p>
<p>bash-4.4# lsmcode -c [ displays the platform system firmware ] </p>
<p>bash-4.4# lsps -a [paging info]</p>
<p>bash-4.4# lspv [ The lspv command displays information about the physical volume ]</p>
<p>bash-4.4# lsvg [  To determine a volume group's ](Take each vg)</p>
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
<p>errpt</p>
<p>errpt -i -j err_code </p>
<p>errclear 0</p>

## cluster
bash-4.4# cd /usr/es/sbin/cluster/utilities<br>
bash-4.4# ./clRGinfo -p
## vios (padmin)
$ set -o emacs [tells the shell to understand Emacs editing commands e.g. backspace key]<br>
$ hostname<br> 
$ ioslevel<br>
$ lsmap -all<br>
$ lsmap -all -net<br>
$ lsmap -all -npiv<br>
$ r o
#lsps -a
#lsps -a
#lspv 
#lsvg
#lsvg -p rootvg
#lsvg -l rootvg (Take every vg)
#df -g
<p>
#lsdev -Cc disk<br>
#lsdev -Cc adapter<br>
#lsdev -Cc memory<br>
#lsdev -Cc processor<br>
#lsdev -Cc tape<br>
#lsdev -Cc planar<br>
</p>




