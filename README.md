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

Configure Homebrew in your /home/usuario/.profile by running
```    
echo 'eval $(/home/linuxbrew/.linuxbrew/bin/brew shellenv)' >> /home/usuario/.profile
```

Add Homebrew to your PATH
```
eval $(/home/linuxbrew/.linuxbrew/bin/brew shellenv)
```

Install GCC by running
```
brew install gcc
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

5. Install Hub

*hub is a command line tool that wraps git in order to extend it with extra features and commands that make working with GitHub easier.*

```
brew install hub
```

```
$ hub version
git version 2.17.1
hub version 2.14.2
```

6. Install GHI

*GitHub Issues on the command line*

```
brew install ghi
```

```
$ ghi version
ghi version 1.2.0
```

7. Install NVM
*Node Version Manager*

```
git clone https://github.com/nvm-sh/nvm.git .nvm
```
```
~/.nvm$ git checkout v0.35.3
HEAD está ahora en 258938e v0.35.3
```
Activate *nvm*
```
~/.nvm$ . nvm.sh
```
Verify that nvm installed
```
$ command -v nvm
nvm
```

8. Install Node via NVM

```
$ nvm install node
```
```
$ node --version
v14.4.0
```

9. Install JSHint 
*Project Repository*

```
$ npm install -g jshint
```
```
$ jshint --version
jshint v2.11.1
```

10. Install VIM
*VIM plugin and command line tool for running JSHint.* <br/>
*This plugin is a front for the jshint NodeJS cli module. This plugin will allow you to run jshint from vim, and shows the results in a split window.*

```
mkdir -p ~/.vim/autoload ~/.vim/bundle && \
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim
```
```
$ vim ~/.vimrc
$ cd ~/.vim/bundle && \
> git clone https://github.com/tpope/vim-sensible.git
```
Now sensible.vim is installed.

```
~/.vim/bundle$ git clone https://github.com/scrooloose/syntastic.git
```

```
$ cd /home/usuario/myapp
$ vim package.json 
```
![VIM :SyntasticInfo](/images/vim.png)


