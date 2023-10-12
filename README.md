# GitHub Organization using API writtten in Shell Scripting 
 
You can communicate with an application using below

- CLI
- API

---
## In this Project we will be listing the users that have permission to a repository in a GitHub Organization using Shell Scripting

We have a shell Script written retrieve information about users from GitHub using GitHub Token, Username and REST API expression

All the commands are written in shell and executed in Ubuntu Server 

1. Clone the repository

```
git clone https://github.com/Pavan-1997/GitHub_Organization_API_Shell.git
```


2. Pass the enviroment variables for GitHub Username and GitHub Token which is later accessed by the script during execution

```
export username="User-Name"
export token="Token"
```


3. Install JQ to extract the data from JSON

```
sudo apy install jq -y
```

6.
7. Give full permission to the cmds.sh file

```
chmod 777 cmds.sh
```


4. Now execute the file by passing the parameters for Organization Name and Repository Name

```

