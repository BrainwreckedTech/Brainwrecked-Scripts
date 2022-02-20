
About This Repository
=====================

This repository is just a collection of scripts that I've come up with
and/or found over time that I think are useful enough to share.
All scripts licensed under the GPL v3 unless otherwise stated.

If you're wondering what happened to a script you could have sworn you
found here before, jump to the bottom for a list of deprecated scripts.

Active Scripts
--------------

These are scripts that I use with at least moderate frequency, so I'll
notice any problems that crop up rather quickly.

``archtype``
  List system CPU architecture, reported by GCC

``backup-root-rsync``
  Backup root partition to another PC via rsync

``convert2ico``
  Converts an image to .ico format

``fakefiletime``
  Fake a file's time relative to other files.

``get-systemd-services``
  Shortcut to list systemd services (omit systemd-*.service)

``gmi``
  Get Machine Info - Prints a line with HW/OS info

``greatpkg``
  List space pkgs are taking up (<http://bbs.archlinux.org/viewtopic.php?pid=1493345#p1493345>)

``gua``
  Guided User Add

``iptmod``
  Changes firewall rules

``myip4``
  Gets IP addresses (local and public)

``netinfo``
  Displays network information (udev/networkd/et al).

``pacctl``
  Pacman helper

``xcbmanip``
  Manipulates the X Clipboard.

Inactive Scripts
----------------

These are scripts I haven't used in some time.  If they stop working,
I'll remove them.

``erc``
  Edit Root Crontab.  Shortcut for editing root's crontab with nano.

``git-auto-add-commit-push``
  Add files to, commit, and push to a git repo

``monitor_off``
  Turn off monitor (Vinicius, license unknown)

``mysql-backup``
  Backup a MySQL database with individual files for each table

``sendEmail``
  Send email from CLI (Brandon Zehm, GPL v2)

Deprecated Scripts
------------------

These scripts either moved elsewhere or fell into such disuse that they
have most likely become obsolete.

``bdmap``
  Evolved to ``scsictl`` at https://git.bwt.com.de/bwt/disk

``hddfill``
  Evolved to ``filldev`` at https://git.bwt.com.de/bwt/disk

``ckinfo``
  Deleted as I stopped using ck-patched kernels a long time ago and haven't kept up

``cur-linux-ver``
  Used in conjunction with ck-patched kernels.  See ``ckinfo``

``cp2chroot``
  Moved to https://git.bwt.com.de/bwt/ssh

``diskspeed``
  Moved to ``drvspeed`` at https://git.bwt.com.de/bwt/disk

``dump-disk-info``
  Moved to ``ddi`` at https://git.bwt.com.de/bwt/disk

``mkminchroot``
  Moved to https://git.bwt.com.de/bwt/ssh

``qvms``
  Completey abandoned in favor of ``qcl`` at https://github.com/BrainwreckedTech/qemu-launcher

``remote-<reboot|shutdown>``
  These two scripts solved a problem where an SSH connection would hang
  in the current terminal until some timeout was reached.  Haven't had
  this problem in a *long* time.

``ssh-authlock-toggle``
  Moved to ``sshauth`` at https://git.bwt.com.de/bwt/ssh

``sshd-passwds-toggle``
  Moved to ``sshdpw`` at https://git.bwt.com.de/bwt/ssh

``startvbvm``
  Precursor to qvms that utilized VirtualBox

``update-nano-syntax-highlight``
  Unnecessary as a nanorc file can include an entire directory of .nanorc files
  (Not sure if nano always supported this or introduced it some time after I
  created the script.)
