
<p><h1>What is procfs and /proc?</h1></p>

<p><h2>Proc is "Process"</h2></p>

<p>Processes, Meta Deta, Data Structures, will be recorded in /proc</p>

<p>Allows us to view data structures, as well as modify some of the on the fly.</p>

<p>The kernel will complete provided instructions immediately (no reboot needed)</p>

<p><h1>udev</h1></p>

<p>Responsible for dynamic device management needed for hot plugging devices.</p>

<p>When the kernel detects a new device being mounted udev gets that signal, it will then trigger and event to systemd/udev/daemon,
that daemon creates a file entry in /dev, it may auto-mount it depending on the rules for the device.</p>

<p>When devices are removed, udev will unmount it and tear down the /dev name</p>

<p>systemd-udevd.service daemon takes care of this.</p>


