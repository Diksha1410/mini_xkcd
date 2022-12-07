
### The simplest and recommended method is to download MySQL Installer (for Windows)

**Step 1**: Download MySQL Installer from https://dev.mysql.com/downloads/installer/ and execute it.

**Step 2**: Determine the setup type. Go for default option called "Developer Default"

**Step 3**: Begin the server configuration by following the onscreen instructions

        - Whenever selection options available "select all of them"
        - Choose MYSQL Root password and you must "remember it"
        

############ INSTALLATION IS COMPLETE AT THIS POINT #############

***************ON MYSQL SHELL***************

```markdown
**Step 1**: open MYSQL Shell

**Step 2**: \sql

**Step 3**: \connect root@localhost

**Step 4**: Please provide the password for 'root@localhost': *******

**Step 5** Save password : n

**Step 6**: show databases;
```


*******************ON COMMAND PROMPT*******************

```markdown
**Step 1**: "C:\Program Files\MySQL\MySQL Server 8.0\bin\mysqlshow" -p

**Step 2**: Password of MySql root: ( Your Password that you created at installation time )

**Step 3**: show databases;
```

```python
If results_are_visible:
        print("you are DONE !!!")     
```
