# p01-t1-iaas-elenaminyaeva


1. Node.js Installation

VM IP: 192.168.20.26
Ubuntu 1804

```
node --version
v8.10.0
```

2. Create my working directory

```
mkdir myapp
cd myapp/
npm init
```

```
root@ubuntu:/home/usuario/myapp# ls
package.json
```

```
root@ubuntu:/home/usuario/myapp# npm install express --save
app.js@1.0.0 /home/usuario/myapp
```

3. Install Homebrew

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

```
sudo apt-get install build-essential
```

4. Git Alias

```
$ git config --global alias.co checkout
$ git config --global alias.br branch
$ git config --global alias.ci commit
$ git config --global alias.st status
```

```
nano ~/.gitconfig
```

test
```
git ci -m "test"
En la rama master
Tu rama está actualizada con 'origin/master'.

nada para hacer commit, el árbol de trabajo está limpio
```

