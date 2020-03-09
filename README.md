# bash scripts

<img src="bash-icon.png"> personal bash scripts collection


## Usage

### clone this repo

```
cd ~/Desktop
git clone https://github.com/MarkHershey/bash-scripts.git
```

### copy the bash script to `~/bin`

```
cd ~
mkdir bin
cp ~/Desktop/bash-scripts/bin/gitignore ~/bin/gitignore

```

### make the script executable

```
cd ~/bin/
chmod u=wrxr gitignore
```

### add `~/bin` into your environments variable

Depends on which shell you are using.

If you are using Bash Shell, open the`.profile` file using nano.

```
nano ~/.profile
```
If you are using ZSH or Z Shell, open the`.zprofile` file using nano.

```
nano ~/.zprofile
```

Add the following line at the top of the file you have opened.

```
export PATH=$PATH:~/bin
```


Save and exit the nano editor.

```
Control + X
Y
Enter
```


Close all Terminal windows and quit Terminal entirely. Open Terminal again, check environment variable by using this command:

```
echo $PATH
```

### Execute the bash script from anywhere

```
cd project_folder/
gitignore
```
