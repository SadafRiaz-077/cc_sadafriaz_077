# ?? Operating Systems — Lab 04  
### **Student Information**  
**Name:** Sadaf Riaz  
**Roll No:** 2023-BSE-077  
**Class:** BSE5-B  

---

## ?? Overview  
This lab focuses on using the Linux Command Line Interface (CLI) to perform essential system administration operations — from verifying VM resources to managing files, users, and processes.

---

## ?? **Task 1 – Verify VM Resources in VMware**  
### • Check Virtual Machine Settings  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/01vm_settings.png)

---

## ?? **Task 2 – Start VM and Log In via SSH**  
### • SSH Login from Host Terminal to VM  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/02vm_login.png.png)

### • Verify Current User and Working Directory (whoami & pwd)  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/03whoami_pwd.png)

---

## ??? **Task 3 – Filesystem Exploration and Hidden Files**  
### • View Root Directory  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/04ls_root.png)

### • Explore /bin Directory  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/05ls_bin.png)

### • Explore /sbin Directory  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/06ls_sbin.png)

### • Explore /usr Directory  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/07ls_usr.png)

### • Explore /opt Directory  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/08ls_opt.png)

### • Explore /etc Directory  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/09ls_etc.png)

### • Explore /dev Directory  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/10ls_dev.png)

### • Explore /var Directory  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/11ls_var.png)

### • Explore /tmp Directory  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/12ls_tmp.png)

### • List Home Directory Contents  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/13home_ls.png)

### • Record Answers in answers.md  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/14answers_md.png)

---

## ?? **Task 4 – Essential CLI Tasks (Navigation & File Operations)**  
### • Create Workspace Directory  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/15mkdir_workspace.png)

### • Change to Workspace Directory  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/16cd_workspace.png)

### • Display Current Path (pwd)  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/17cd_workspace.png)

### • Create File using Nano  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/18nano_readme.png)

### • Create Second File using Nano  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/19nano_main.png)

### • Create Environment File using Nano  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/20nano_env.png)

### • List Files in Workspace  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/21workspace_ls.png)

### • Copy File Using cp Command  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/22cp_readme.png)

### • Move File Using mv Command  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/23mv_readme.png)

### • Remove File Using rm Command  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/24rm_readme.png)

### • Create Directory for Java App  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/25mkdir_java_app.png)

### • Copy Folder Recursively  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/26cp_recursive.png)

### • Verify Copied Folder  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/27copy_verify.png)

### • Display Command History  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/28history.png)

---

## ?? **Task 5 – System Info, Resources & Processes**  
### • Display System Information (uname)  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/29uname.png)

### • View CPU Information  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/30cpuinfo.png)

### • View Memory Information  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/31meminfo.png)

### • Check Disk Usage  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/32diskinfo.png)

### • Display OS Release Info  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/33os-release.png)

### • List Running Processes  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/34processes.png)

---

## ?? **Task 6 – User and Account Verification**  
### • Create New User (adduser)  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/35adduser_lab4user.png)

### • Set Password for New User  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/36lab4user_passwd.png)

### • Switch to New User (su command)  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/37su_lab4user.png)

### • Verify Admin Access Using sudo  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/38sudo_whoami.png)

### • Return to Original User  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/39exit_back.png)

### • Delete Created User (Optional)  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/40deluser.png)

---

## ?? **Bonus Task 7 – Demo Script**  
### • Create Demo Script Using Nano  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/41nano_run_demo.png)

### • Grant Execute Permission (chmod)  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/42chmod_run_demo.png)

### • Run Demo Script  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/43run_demo_output.png)

### • Run Script with Sudo (Optional)  
![](C:/Users/Lenovo/OneDrive/Desktop/cc_sadafriaz_077_lab-2/lab%204/Screenshots/44run_demo_output_sudo.png)

---

## ? **Conclusion**  
This lab demonstrated Linux commands for exploring directories, file operations, system information, user management, and creating executable scripts.  
It provided hands-on experience in using core CLI commands to manage and understand a Linux environment.

---

### ? *Prepared by:*  
**Sadaf Riaz (2023-BSE-077)**  
Department of Software Engineering
