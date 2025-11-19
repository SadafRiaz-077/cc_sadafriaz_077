
CC Lab 06 – Linux Users, Groups, Permissions & Shell Scripting

Student: Sadaf Riaz
Roll No: 2023-BSE-077
Section: BSE-5B
# Lab 06 – User Management, Permissions, Scripts, and Commands
**Student:** Sadaf Riaz  
**Roll No:** 2023-BSE-077  
**Class:** BSE5-B  

---

## 🟦 Task 1 – Switch to Root with `su -`
### Screenshots:
![Set Root Password](Screenshots/01task1_set_root_password.png)  
![Switch to Root](Screenshots/02task1_su_root.png)  
![Exit to Normal User](Screenshots/03task1_exit_to_user.png)  

---

## 🟦 Task 2 – Create User *tom* & Verify in passwd/group/shadow
![Create User tom](Screenshots/04task2_adduser_tom.png)  
![Verify passwd](Screenshots/05task2_verify_passwd.png)  
![Verify group](Screenshots/06task2_verify_group.png)  
![Verify shadow](Screenshots/07task2_verify_shadow.png)  

---

## 🟦 Task 3 – Groups: Primary & Secondary Group Changes
![Create Groups](Screenshots/08task3_groupadd.png)  
![Change Primary Group](Screenshots/09task3_change_primary_group.png)  
![Add Secondary Groups](Screenshots/10task3_add_secondary_groups.png)  
![Reset Secondary Groups](Screenshots/11task3_reset_secondary_groups.png)  

---

## 🟦 Task 4 – Create/Delete Users & Groups (Jerry, Scooby, jolly, anime)
![Create Users](Screenshots/12task4_add_users.png)  
![Scooby su Failure](Screenshots/13task4_scooby_su_auth_failure.png)  
![Set Scooby Password](Screenshots/14task4_set_password_scooby.png)  
![Scooby No Home Directory](Screenshots/15task4_scooby_su_no_home.png)  
![Home Missing](Screenshots/16task4_scooby_no_home.png)  
![Create Home Directory](Screenshots/17task4_scooby_create_home.png)  
![Scooby Login Success](Screenshots/18task4_scooby_login_success.png)  
![Verify Users](Screenshots/19task4_verify_users.png)  
![Shell Switching](Screenshots/20task4_shell_switching.png)  
![Verify Groups](Screenshots/21task4_verify_groups.png)  
![Delete Groups](Screenshots/22task4_delete_groups.png)  
![Delete Users](Screenshots/23task4_delete_users.png)  

---

## 🟦 Task 5 – Create Student, Files & Ownership Management
![Create Student](Screenshots/24task5_create_student.png)  
![Create Files](Screenshots/25task5_create_files.png)  
![chown file1](Screenshots/26task5_chown_file1.png)  
![chgrp file1](Screenshots/27task5_chgrp_file1.png)  
![File Types](Screenshots/28task5_file_types.png)  
![Exit Student](Screenshots/29task5_exit_student.png)  

---

## 🟦 Task 6 – Change Permissions (Symbolic)
![Switch to Student](Screenshots/30task6_su_student.png)  
![Remove All](Screenshots/31chmod_remove_rwx.png)  
![Add Read](Screenshots/32task6_chmod_add_r.png)  
![User Execute](Screenshots/33task6_chmod_u_plus_x.png)  
![User & Group Write](Screenshots/34task6_chmod_ug_plus_w.png)  
![Remove All Explicit](Screenshots/35task6_chmod_ugo_minus_rwx.png)  

---

## 🟦 Task 7 – Change Permissions using Set Symbolic (u= g= o=)
![Student Context](Screenshots/36task7_student_context.png)  
![Set All to rwx](Screenshots/37task7_chmod_set_all_rwx.png)  
![Remove Exec from Group & Others](Screenshots/38task7_remove_exec_go.png)  
![Remove All Permissions](Screenshots/39task7_remove_all_perms.png)  

---

## 🟦 Task 8 – Numeric (Octal) Permissions
![Student Context](Screenshots/40task8_student_context.png)  
![chmod 777](Screenshots/41task8_chmod_777.png)  
![chmod 700](Screenshots/42task8_chmod_700.png)  
![chmod 744](Screenshots/43task8_chmod_744.png)  
![chmod 640](Screenshots/44task8_chmod_640.png)  
![chmod 664](Screenshots/45task8_chmod_664.png)  
![chmod 775](Screenshots/46task8_chmod_775.png)  
![chmod 750](Screenshots/47task8_chmod_750.png)  

---

## 🟦 Task 9 – Pipes, grep, Redirects
![grep + less](Screenshots/48task9_grep_less.png)  
![grep + more](Screenshots/49task9_grep_more.png)  
![grep head](Screenshots/50task9_grep_head.png)  
![Redirect Overwrite](Screenshots/51task9_redirect_overwrite.png)  
![Redirect Append](Screenshots/52task9_redirect_append.png)  

---

## 🟦 Task 10 – Script setup.sh (Variables, Checks, Substitution)
![B1 – Shebang](Screenshots/53task10_b1_vim.png)  
![B1 – Run](Screenshots/54task10_b1_run.png)  
![B2 – var1](Screenshots/55task10_b2_vim.png)  
![B2 – Run](Screenshots/56task10_b2_run.png)  
![B3 – ls -l Variable](Screenshots/57task10_b3_vim.png)  
![B4 – Directory Check](Screenshots/58task10_b4_vim.png)  
![B4 – Run](Screenshots/60task10_b4_run.png)  
![B5 – File Check](Screenshots/61task10_b5_vim.png)  
![B5 – Run](Screenshots/62task10_b5_run.png)  
![B6 – Permission Checks](Screenshots/63task10_b6_vim.png)  
![B6 – Run](Screenshots/64task10_b6_run.png)  

---

## 🟦 Task 11 – setup.sh (Numeric & String Tests)
![Numeric eq](Screenshots/67task11_b1_vim.png)  
![Numeric ne](Screenshots/69task11_b2_vim.png)  
![Numeric gt](Screenshots/71task11_b3_vim.png)  
![Numeric lt](Screenshots/73task11_b4_vim.png)  
![Numeric ge](Screenshots/75task11_b5_vim.png)  
![Numeric le](Screenshots/77task11_b6_vim.png)  
![String =](Screenshots/79task11_b7_vim.png)  
![String !=](Screenshots/81task11_b8_vim.png)  
![String -z](Screenshots/83task11_b9_vim.png)  

---

## 🟦 Task 12 – For Loop Arguments
![B1](Screenshots/85task12_b1_vim.png)  
![B1 Run](Screenshots/86task12_b1_run.png)  
![B2](Screenshots/87task12_b2_vim.png)  
![B2 Run](Screenshots/88task12_b2_run.png)  

---

## 🟦 Task 13 – While Loop & Functions
![While Loop](Screenshots/91task13_b2_vim.png)  
![While Loop Run](Screenshots/92task13_b2_run.png)  
![Sum Function](Screenshots/93task13_b3_vim.png)  
![Sum Function Run](Screenshots/94task13_b3_run.png)  
![Sum Arguments](Screenshots/95task13_b4_vim.png)  
![Sum Arguments Run](Screenshots/96task13_b4_run.png)  

---

## 🟦 Task 14 – Codespaces GUI
![Fork Repo](Screenshots/97task14_fork.png)  
![Launch Codespace](Screenshots/98task14_codespace_launch.png)  
![Start Script ls](Screenshots/99task14_start_script_ls.png)  
![Run Script](Screenshots/100task14_start_run.png)  
![Ports View](Screenshots/101task14_ports_view.png)  
![VNC URL](Screenshots/102task14_vnc_url.png)  
![VNC Password](Screenshots/103task14_vnc_password_prompt.png)  
![VNC Desktop](Screenshots/104task14_vnc_desktop.png)  
![Stop GUI](Screenshots/105task14_stop_run.png)  

---

# 🟩 Exam Evaluation Questions (EEQs)

## **Q1 – Group Management and Membership**
![Groups Created](Screenshots/106Q1_groups_created.png)  
![Group Changes](Screenshots/107Q1_group_changes.png)  
![Verify Groups](Screenshots/108Q1_group_verification.png)  

---

## **Q2 – Ownership & Permissions**
![chown & chgrp](Screenshots/109Q2_chown_chgrp.png)  
![Symbolic & Numeric](Screenshots/111Q2_symbolic_numeric.png)  
![Verify Permissions](Screenshots/112Q2_permissions_ls.png)  

---

## **Q3 – Pipes, Grep, Redirection**
![grep + pipe](Screenshots/113Q3_grep_pipe.png)  
![Redirect Overwrite & Append](Screenshots/114Q3_redirect_overwrite_append.png)  

---

## **Q4 – Script Variables & Command Substitution**
![var1](Screenshots/115Q4_step1_var1.png)  
![All Files](Screenshots/117Q4_step2_allfiles.png)  
![Check Dir/File](Screenshots/118Q4_step3_dirfile_checks.png)  

---

## **Q5 – Numeric & String Comparisons**
![eq Examples](Screenshots/119Q5_eq_examples.png)  
![Numeric Tests](Screenshots/120Q5_numeric_tests.png)  
![String Tests](Screenshots/121Q5_string_tests.png)  

---

## **Q6 – For Loop**
![For Loop Vim](Screenshots/122Q6_script_forloop_vim.png)  
![For Loop Run](Screenshots/123Q6_forloop_run.png)
  
---

## **Q7 – While Loop & Function**
![Function Output](Screenshots/125Q7_script_output.png)  

---

# ✅ End of README
