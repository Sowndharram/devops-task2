# Task 5

## Install Maven
```bash
sudo apt install maven
```
![image](https://github.com/user-attachments/assets/a1c7b760-d02d-403d-8213-48898f1ce463)


## Configure Jenkins
 - In Jenkins go to `configure jenkins` > `tools`
 - Locate JDK section
 - Uncheck `Install Automatically`
 - Name `Java 17`
 - Go to terminal and enter the command and get the java 17 path:

```bash
update-java-alternatives --list 
```

 - paste the java path in `JAVA_HOME`
![photo_2025-03-22_14-29-48](https://github.com/user-attachments/assets/58dbd308-3d1d-43eb-9e82-38ae31258e62)


## Fork The Repo and build the pipeline
![photo_2025-03-22_14-30-06](https://github.com/user-attachments/assets/3896ee1e-e4bb-4149-bf26-3af2f870c52b)
