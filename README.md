# Turbo Plus

**Superfast** deploy Rails applications.


# Suggestions
Copy file from server to local computer (Mac OS)
```
scp deployuser@myapp.com:/home/deployuser/filename /Users/localuser/Desktop/filename
```

```
insert this in .bash_profile file ->>>>> source "$HOME/turbo-plus/app.bash"
```


Connect to some host is easy now:
```Bash
# Set in file -> ~/.ssh/config
$ ssh best_server_name
```

```Bash
# copying files and folders from your app to -> ~/apps/currentfoldername
$ turbo send
```

```Bash
# setups jobs for deploy
# you should to still stay in your git downloaded folder
$ turbo build
```

```Bash
# restart nginx or sidekiq
# you should to still stay in your git downloaded folder
$ turbo restart ng (sq)
```
