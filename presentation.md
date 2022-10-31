title: Internship Presentation
author:
  name: Jason Wong
  url: https://github.com/jaosn0412
style: basic-style.css
output: presentation-cleaver.html

---

# Internship for Digital Business

## MIDF 2022-2023

---

# Week 1

## 11 October 2022 to 14 October 2022

---

### 11 October 2022

- Setup new laptop provided by GIT
- Installed WSL2 on windows
- Learned about COWSAY commands
- Learned about navigating in linux with terminal commands

---

### 12 October 2022 commands

| Command | Description | Remarks |
|---|---|---|
|`shutdown -r -t 5`| restarts the computer after 5 seconds | this is a windows command |
|`uname -a`| prints the system kernel and local machine info |  |
| `apt` | manage packages available for install in ubuntu | package manager for Ubuntu |
| `ip addr` | prints addesses available for each network interface | another command alike `ifconfig` |

---

### 13 October 2022

- Pull Request:
– also referred to as a merge request
– is an event that takes place in software development when a contributor/developer is ready to begin the process of merging new code changes with the main project repository.

---
### 13 October 2022 Commands

| Command | Description | Remarks |
|---|---|---|
| `lsb_release -a` | Show the version of Ubuntu, release, and codename. |  |
| `cowsay -e TT huhu` | Change the cow’s eye to ‘TT’ and let cow say ‘huhu’. | -f : change cow to turtle. |
| `sudo` | Allows a permitted user to execute a command as the superuser or another user. |  |
| `man` | This is a manual to get an explanation. |  |

---

### 14 October 2022

| Command | Description | Remarks |
|---|---|---|
| `>` | Copy the output into the file and become contents with replace its contents. |  |
| `>>` | Copy the output into the file and become contents without change its contents. |  |
| `clear` | To clear all the commands in the terminal. | |
| `cat` | Concatenate files and print on the standard output. by different ways. | another command alike `less/ more/ vi` |

Vocabulary:
| drwx | d:directory; r:read; w:write; x:execute |

---

# Week 2

## 17 October 2022 - 21 October 2022

---

### 17 October 2022

| Command | Description | Remarks |
|---|---|---|
| `ssh-keygen` | Used to generate public key and private key for SSH. | |
| `id_rsa` | A private key. | The default name for SSH key pairs is id_rsa , and that name will allow an SSH client to locate the key automatically. |
| `id_rsa pub` | A public key. |  |

---

### 18 October 2022

| Command | Description | Remarks |
|---|---|---|
| `git status` | To show the status of each files. |  |
| `git commit` | Captures a snapshot of the project's currently staged changes. |  |
| `npm install` | To install dependencies of the project. |  |
| `npm run debug` | To run the project. | another command alike `npm run start` |


---

### 19 October 2022

####  Step for getting changes from remote:
- 1: git fetch origin
- 2: git pull origin [branch name]

####  Step for pushing changes into remote:
- 1: git status
- 2: git add [file name]
- 3: git commit -m "[commit messages]"
- 4: git push origin [branch name]

---

### GIT workflow

Below is the git workflow

![Git workflow](Git_Concept.jpg)

Legend on the next page.

---

### GIT workflow

1. `git init`
1. `git remote add origin`
1. `git add [filename]`
1. `git commit -m "msg"`
1. `git push origin branch`
1. `fork`
1. `Pull Request`
1. `git fetch origin`
1. `git pull origin branch`

---

### Distributed vs Centralized Version Control

|Distributed | | Centralized|
|---|---|---|
|clone/fork|*download terminology*|checkout|
| logs, diffs are stored in each clones | *storage* | the logs, diffs are stored in the central server |
| each clones/fork is the full copy of the repository | *downloaded copy* | each checkout copy is a snapshot of the current version being checked out version |

---

### Distributed vs Centralized Version Control

|Distributed | | Centralized|
|---|---|---|
| branching is promoted and easy to perform | *branching* | branching is controlled and require proper management |
| each clones/for may or may not be similar between clones/fork | *clones/checkout* | each checkout conforms to the central version|
|git, mercurial|*known version control names*|subversion, cvs, clearcase|

---

### Distributed vs Centralized Version Control

![Distributed vs Centralized](https://media.springernature.com/lw685/springer-static/image/chp%3A10.1007%2F978-1-4842-8658-6_1/MediaObjects/518274_1_En_1_Fig9_HTML.png)

---
### More Commands Learned

| Command | Description | Remarks |
|---|---|---|
| `init` | Initializer. To set up a new or existing package. |  |
| `history` | List out all the commands inserted before. |  |
| `cd` | Get into the directory if with the directory name. | If not, then it will back to home page. |
| `git` | To keep track every changes of the file. |  |

---

# END
