
<p><h1>Virtual Files</h1></p>

<p>Linux uses several virtual filesystems to provide an in-memory look into the system<br>
They are virtual files because nothing is actually written to your device, they provide insight into kernal data structures and your system hardware.</p>

<p><h1>SysFS Filesystem and /sys</h1></p>

<p>sysfs is a filesystem that allows kernel subsystems to export kernel objects, oject attributes,and object relationships to the user space.</p>

<p>You will not find a mount for it in /etc/fstab</p>

<p>sysfs and proc are mounted on system-boot.</p>
