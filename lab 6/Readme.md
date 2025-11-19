
CC Lab 06 – Linux Users, Groups, Permissions & Shell Scripting
Student: Sadaf Riaz
Roll No: 2023-BSE-077
Section: BSE-5B

 Task 1 – Switching to Root
* Set root password
31task1_set_root_password.png
* Switch to root
02task1_su_root.png
* Return to normal user
03task1_exit_to_user.png

 Task 2 – Create User tom & Verify Files
* Create user
04task2_adduser_tom.png
* Verify /etc/passwd
05task2_verify_passwd.png
* Verify /etc/group
06task2_verify_group.png
* Verify /etc/shadow
07task2_verify_shadow.png

Task 3 – Group Creation & Managing User Groups
* Create groups
08task3_groupadd.png
* Change primary group
09task3_change_primary_group.png
* Add secondary groups
10task3_add_secondary_groups.png
* Reset secondary groups
11task3_reset_secondary_groups.png

 Task 4 – Create/Delete Users & Groups
* Create users
12task4_add_users.png
* Failed Scooby login
13task4_scooby_su_auth_failure.png
* Set Scooby password
14task4_set_password_scooby.png
* Scooby login without home
15task4_scooby_su_no_home.png
* Verify Scooby home missing
16task4_scooby_no_home.png
* Create home directory
17task4_scooby_create_home.png
* Scooby login success
18task4_scooby_login_success.png
* Verify users
19task4_verify_users.png
* Change shell
20task4_shell_switching.png
* Verify groups
21task4_verify_groups.png
* Delete groups
22task4_delete_groups.png
* Delete users
23task4_delete_users.png

 Task 5 – Create Student User & File Ownership
* Create student user
24task5_create_student.png
* Create files
25task5_create_files.png
* chown on file1
26task5_chown_file1.png
* chgrp on file1
27task5_chgrp_file1.png
* Identify file types
28task5_file_types.png
* Exit student
29task5_exit_student.png

Task 6 – Symbolic Permissions
* Switch to student
30task6_su_student.png
* Remove rwx
31chmod_remove_rwx.png
* Add read
32task6_chmod_add_r.png
* Add execute to user
33task6_chmod_u_plus_x.png
* Add write to user & group
34task6_chmod_ug_plus_w.png
* Remove all rwx
35task6_chmod_ugo_minus_rwx.png

 Task 7 – chmod using u= g= o=
* Student context
36task7_student_context.png
* Set all rwx
37task7_chmod_set_all_rwx.png
* Remove exec for group & others
38task7_remove_exec_go.png
* Remove all permissions
39task7_remove_all_perms.png

 Task 8 – Numeric Permissions
* Student context
40task8_student_context.png
* chmod 777 ? full access
41task8_chmod_777.png
* chmod 700
42task8_chmod_700.png
* chmod 744
43task8_chmod_744.png
* chmod 640
44task8_chmod_640.png
* chmod 664
45task8_chmod_664.png
* chmod 775
46task8_chmod_775.png
* chmod 750
47task8_chmod_750.png

 Task 9 – Grep, Pipes & Redirects
* grep + less
48task9_grep_less.png
* grep + more
49task9_grep_more.png
* grep with head
50task9_grep_head.png
* Redirect overwrite
51task9_redirect_overwrite.png
* Redirect append
52task9_redirect_append.png

Task 10 – Script Basics
* Shebang
53task10_b1_vim.png / 54task10_b1_run.png
* var1
55task10_b2_vim.png / 56task10_b2_run.png
* ls -l into variable
57task10_b3_vim.png
* Directory check
58task10_b4_vim.png / 60task10_b4_run.png
* File check
61task10_b5_vim.png / 62task10_b5_run.png
* Permission check
63task10_b6_vim.png / 64task10_b6_run.png

Task 11 – Numeric & String Tests
* Variables
65task11_b0_vim.png / 66task11_b0_run.png
* Numeric tests
b1–b6 screenshots
* String tests (=, !=, -z)
79–84task11_b7_b9.png

 Task 12 – For Loop Arguments
* Script
85task12_b1_vim.png
* Output
86task12_b1_run.png
* For loop
87task12_b2_vim.png
* Output
88task12_b2_run.png

Task 13 – Loops & Functions
* Shebang
89task13_b1_vim.png
* While-loop summation
91task13_b2_vim.png / 92task13_b2_run.png
* Interactive sum function
93task13_b3_vim.png / 94task13_b3_run.png
* Sum args function
95task13_b4_vim.png / 96task13_b4_run.png

 Task 14 – GitHub Codespaces GUI
* Fork
97task14_fork.png
* Launch Codespace
98task14_codespace_launch.png
* Verify script
99task14_start_script_ls.png
* Run GUI start script
100task14_start_run.png
* Ports
101task14_ports_view.png
* VNC
102–104task14_vnc.png
* Stop GUI
105task14_stop_run.png

 Exam Evaluation Questions
Q1 – Groups
Screenshots:
106Q1_groups_created.png
107Q1_group_changes.png
108Q1_group_verification.png

Q2 – Ownership & Permissions
109Q2_chown_chgrp.png
111Q2_symbolic_numeric.png
112Q2_permissions_ls.png

Q3 – Pipes, Grep, Redirect
113Q3_grep_pipe.png
114Q3_redirect_overwrite_append.png

Q4 – Script Variables & File Checks
115Q4_step1_var1.png
117Q4_step2_allfiles.png
118Q4_step3_dirfile_checks.png

Q5 – Numeric & String Tests
119Q5_eq_examples.png
120Q5_numeric_tests.png
121Q5_string_tests.png

Q6 – For Loop
122Q6_script_forloop_vim.png
123Q6_forloop_run.png

Q7 – While Loop & Functions
125Q7_script_output.png


