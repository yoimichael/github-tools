# github-tools
This is a simple tool that helps you invite github users to your organization or your team.

## Prepare
make sure **members.csv** contains all github usernames to add. Each username is separated by a new line.

### 1. Add users to your organization 
```
python gt.py -o username password org_name
```
### 2. Add users to your team 
```
python gt.py -t username password org_name team_name
```

## 
Note: ```username``` and ```password``` here are your username and password. Github API requires you to be authenticated in order to add people to your organization/team.

