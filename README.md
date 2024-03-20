# Linux

### What is a virtual machine
  - Through `Software` (hypervisors) to create `virtual machines` with `virtual hardware` and `operating systems`.
    
  ![Linux drawio (1)](https://github.com/Liu-Chen-CS/Linux/assets/158779475/e4f60967-2372-4be6-9623-2ea747809f4e)

### Connect to CentoOS 7
![Snipaste_2024-03-20_15-59-48](https://github.com/Liu-Chen-CS/Linux/assets/158779475/bd4492db-45be-4a42-9e30-e15d226140a0)

### Commend
|**ls** |    [-a]    |    [-l]    |    [-h]    |    [path]    |
|----------------------|--------|--------|--------|--------|
|ls [-a -l -h] [path] |    `displays all files`, including hidden ones    |   `displays` a `long listing format`, showing detailed information    |   Makes file sizes `human-readable`|    path    |

|**cd** |    [path]    |
|--------|--------|
|cd [path] |    `change` the current working `directory`    |
|cd .. |    `move up` one level in the directory hierarchy    |

|**pwd** |        |
|--------|--------|
| pwd |    "print working directory", it `displays` the current `directory` you are in    |

|**mkdir** |    [-p]    |   path     |
|--------|--------|--------|
| mkdir /home/liuchen/test1|    `creates` all necessary  `parent directories` without throwing an error    |    `create` a `directory` called test1  |
 
|**touch** |  file name    |                                                                       
|--------|--------|                                                                                
| touch test2.txt|    `create` a `file` named "text2" in the current directory    |                

|**cat** |  file name    |
|--------|--------|
| cat test1.txt|    `display` the contents of `files`    |

|**more** |  file name    |
|--------|--------|
| more test1.txt|    `display` the contents of a text `file` one screen at a time. It allows you to `scroll through` the file    |
| q |   `quit` the more program   |

|**cp** |  [-r]    |  source path    | destination path    |
|--------|--------|--------|--------|
| cp test1.txt ./test2.txt|   To `copy` a `directory`    |   `copy` test1.txt    |`save` it with name test2.txt    |

|**mv** |  source path    | destination path    |
|--------|--------|--------|
| mv test1.txt /home/liuchen/Desktop|    `move` test1.txt    |`move to` Desktop   |
| mv test1.txt  test3.txt|    `move` test1.txt    |if path can't find, then its `renaming`   |

|**rm** |  [-r]    | file name    |  file name    | .....   |file name  |
|--------|--------|--------|--------|--------|--------|
| rm test1.txt |    `remove` test1.txt   |`remove` test2.txt   |`remove` test3.txt   |`remove` test.....txt   |`remove` test99999.txt   |
| rm -r folder|    `remove` a folder    |

