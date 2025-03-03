# Bash Cheet Sheet

### System links:

```
	ln -sfv <file to link> <symlink>
```

* s - Create a symbolic link
* f - If the target file already exists, then unlink it so that the link may occur.
* v - Cause ln to be verbose, showing files as they are processed.

### See what processes are running

```
  htop
```

or

```
  ps aux | grep php
```

### Copy SSH Key
```pbcopy < ~/.ssh/id_rsa.pub```

### Reload Bash profile
```. ~/.bash_profile```

# Python Related Commands
```
mkvirtualenv --python=/usr/local/bin/python3 --no-site-packages <env>
```
