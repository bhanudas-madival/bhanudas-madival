//# Bhanu | System Administrator → DevOps

System Administrator with 9+ years of infrastructure experience, transitioning into DevOps.
Focused on automation, Linux, cloud, and CI/CD.

---

## 🔧 Core Skills

* Linux Administration
* Networking
* Git & GitHub
* Bash Scripting (Learning)
* AWS (Learning)
* DevOps Fundamentals

---

## 📘 Currently Learning

* Linux automation
* Shell scripting
* Git workflows
* AWS core services
* CI/CD pipelines
* Infrastructure as Code

---

## 📂 Projects

* DevOps Notes
* Linux Commands
* Git Practice
* Automation Scripts

---

## 🎯 2026 Goal

Transition into DevOps Engineer role

---

## 📊 GitHub Stats

![GitHub stats](https://github-readme-stats.vercel.app/api?username=bhanudas-madival\&show_icons=true)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=bhanudas.madival\&layout=compact)

---

⭐ System Administrator → DevOps Engineer

Day 17: Practice Linux basic commands, file operations, permissions, and process management

- Practiced file and directory commands (ls, cd, pwd, mkdir, rm, cp, mv)
- Worked with file viewing and creation commands (cat, less, head, tail, touch)
- Learned text processing commands (sort, uniq, tee)
- Practiced input/output redirection (>, >>) and pipes (|)
- Revised basic file permissions using chmod and chown
- Practiced process management commands (ps, top, kill)Day 17: Practice Linux basic commands, file operations, permissions, and process management

- Practiced file and directory commands (ls, cd, pwd, mkdir, rm, cp, mv)
- Worked with file viewing and creation commands (cat, less, head, tail, touch)
- Learned text processing commands (sort, uniq, tee)
- Practiced input/output redirection (>, >>) and pipes (|)
- Revised basic file permissions using chmod and chown
- Practiced process management commands (ps, top, kill)

Day 18: Practice Linux disk, storage, mount, and log management basics

- Practiced disk usage monitoring using df -h
- Explored block devices using lsblk
- Learned basic mount concepts and verified mounted filesystems
- Explored the /var/log directory structure
- Practiced reading and analyzing Linux log files
- Revised disk and storage fundamentals through hands-on exercises


### ✅ Topics Covered

* User management (`useradd`, `passwd`)
* Group management (`groupadd`, `usermod -aG`)
* Explored `/etc/passwd` and `/etc/shadow`
* File permissions using `chmod` (numeric & symbolic)
* File ownership using `chown`
* Default permissions with `umask`
* Special permissions:

  * SUID
  * SGID
  * Sticky Bit
* Practical: Created users/groups and tested file access restrictions and permissions

### 💻 Hands-on

* Created multiple users and groups
* Added users to supplementary groups
* Verified user account information
* Modified file ownership and permissions
* Tested permission inheritance with `umask`
* Practiced SUID, SGID, and Sticky Bit behavior
* Verified file access by different users

2. Process Management & Debugging
Practiced viewing running processes using ps and top.
Learned to locate specific processes with pgrep.
Practiced job control using jobs, bg, and fg.
Managed processes using:
kill (graceful termination)
kill -9 (force termination)
Studied Linux process states:
Zombie process (Z)
Uninterruptible sleep / stuck process (D state concept)
Completed a hands-on lab by creating CPU load, identifying the resource-consuming process, and terminating it safely.
🔴 3. Disk & Storage Troubleshooting
Checked filesystem usage with df -h.
Monitored inode usage using df -i.
Identified large files and directories with du -sh *.
Simulated a disk-full scenario and practiced troubleshooting and recovery.
Practiced mount troubleshooting:
Verified filesystems using mount -a.
Reviewed and validated /etc/fstab.
🎯 Skills Strengthened
Process monitoring and troubleshooting
Linux job control
Safe process termination
Understanding Linux process states
Disk space and inode troubleshooting
Filesystem mount diagnostics
Practical Linux debugging techniques

Linux – LVM (Snapshots Focus)
Created LVM snapshots using lvcreate -s
Listed logical volumes and snapshots using lvs
Mounted an LVM snapshot and verified filesystem contents
Verified that snapshot data remains unchanged after modifications to the original logical volume
Practiced snapshot merge/restore to roll back the original volume
Understood Copy-on-Write (CoW) behavior of LVM snapshots
Learned what happens when snapshot storage becomes full and why adequate snapshot size is important
Revised basic fdisk concepts and partition table management
💻 Hands-on Practicals
Created an LVM snapshot
Mounted the snapshot and verified stored data
Modified files on the original logical volume
Compared original and snapshot contents
Restored the original logical volume from the snapshot
Verified successful rollback after merge
Explored lvs output before and after snapshot operations
💡 Key Learnings
LVM snapshots capture the state of a logical volume at a specific point in time.
Snapshots use Copy-on-Write (CoW), storing only changed blocks rather than duplicating the entire volume.
If snapshot space becomes full, the snapshot becomes invalid and can no longer be used for recovery.
Snapshot restore provides a fast rollback mechanism after accidental file changes or failed updates.
Proper snapshot sizing is essential for reliable backup and recovery operations.

feat(linux): complete Logs & Debugging practicals

- Explored the /var/log directory and common log files.
- Used journalctl -xe to inspect recent system events and errors.
- Viewed service-specific logs with journalctl -u ssh.
- Practiced filtering logs using grep.
- Analyzed logs based on timestamps/time ranges.
- Learned to distinguish real errors from informational log messages.
- Performed a troubleshooting lab by breaking a service, reading logs,
  identifying the root cause, fixing the issue, and verifying recovery.

Skills practiced:
- Log analysis
- Systemd journal navigation
- Service troubleshooting
- Root cause analysis
- Linux debugging workflow
