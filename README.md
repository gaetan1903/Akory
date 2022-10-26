# akory

A simple typewriter effect command written in bash <img src="https://github.com/RajaRakoto/github-docs/blob/master/dago.gif?raw=true" width=15>



https://user-images.githubusercontent.com/43904633/184029034-1c1cb65e-2008-4373-b5b3-a9429ad96519.mp4



## INSTALLATION 

```s 
sudo wget https://raw.githubusercontent.com/gaetan1903/akory/main/akory -O /usr/local/bin/akory
```

```s 
sudo chmod a+rx /usr/local/bin/akory
```

## USAGE 

### AS PARAMETER 

```s
akory "Hello world " 
```

```s
akory -d 0.2 "Hello world " 
```

```s
akory -d 0.002 "`figlet 'd e  a o n a   a a ? ?'`" | lolcat 
```

```s
akory -d 0.002 "`neofetch`" 
```

### AS PIPE INPUT 

```s
date | akory 
```

```s
echo "Hello world " | akory -d 0.2
```

```s
neofetch |akory -d .001
```


## CONTRIBUTORS

![Image des contributeurs GitHub](https://contrib.rocks/image?repo=gaetan1903/Akory)


