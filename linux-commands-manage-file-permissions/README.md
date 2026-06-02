## File Permissions in Linux

### Overview
This activity demonstrates how Linux file permissions are managed and modified using command-line tools. It focuses on reviewing existing permissions, identifying potential access issues, and applying updates to ensure proper authorization. 

---

### Scenario
As a security professional at a large organization, I am reviewing and managing file system permissions of the research team. 

---

### Goal
Identify if current access levels were appropriate, and modify permissions by removing unauthorized access or granting proper authorization for members in the research team if necessary.

---

### Taken Steps

#### Check file and directory details
- pwd: show the current directory.
- ls: list contents of current directory.
- cd: change directories.
- ls -la: display detailed file information including hidden files and permissions.

#### Describe the permissions string
The 10-character string represents file type and access permissions in Linux: 
- The first character indicates the file type: d for directory / - for regular file. 
- The next nine characters are divided into three groups: Owner, Group, and Others. Each shows r (read), w (write), and x (execute) permissions. A dash (-) means a permission is not granted.

#### Change file permissions
- chmod: change permissions. Example: chmod g+r file1.txt (grant read access to Group of the file text1.txt), chmod g-r file1.txt (remove read access from Group of the file text1.txt).
- ls -l: display detailed file information of visible files.

#### Change file permissions on a hidden file
- .project_x.txt: hidden file (Linux hidden files start with the dot . at the beginning of the filename).

#### Change directory permissions
ls -l and chmod: to authorize proper permissions and verify changes. Command-line features were already described on above steps.

---

### What I Learned?
- How to navigate the Linux file system using basic commands such as pwd, ls, cd, ls -l, and ls -la. 
- Hands-on experience of reviewing file permissions, identifying hidden files, and analyzing the 10-character permission string to understand file type and access levels. 
- Practiced to change permissions by using chmod to remove or grant access for different users. 
- How to verify changes to ensure that update file permissions aligning security requirements.

---

### Notes
More details about lab directions and performed steps could be found in the uploaded documents.
