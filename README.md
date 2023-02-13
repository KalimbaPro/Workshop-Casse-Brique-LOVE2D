# Workshop-Casse-Brique-LÖVE2D
---
## SETUP
```
Before the workshop begin, you must install Lua and LÖVE2d
```
---

### Install Lua
```
------- On Debian, Ubuntu & Mint -------
> sudo apt install lua5.4

------- On Fedora Linux -------
> sudo dnf install lua
```

Check if the installation is complete by using this command :
```sh
> lua -v
```
### Install LÖVE2D
```sh
------ On Debian, Ubuntu & Mint ------
> sudo apt-get install love

------ On Fedora Linux ------
> sudo yum install love
```

## Documentation
---
### If you need it here's the documentation for [LOVE](https://love2d.org/wiki/love)

Check if the installation is complete by using one of this commands (the second is funnier) :
```sh
> love --version
> love
```



## Step 0 : First program and execution
---
You are going to write you first ever program in Lua
- Find a way to create a window in lua
- this window must be named "casse-brique" and must have the following dimenssions (480; 640)

Your window should look like something lile this :
<----- insert imamge

## Step 1 : Now time to make a bar
---
A breackDown need a bar
- Find a way to create an object bar and to print it the previous window
- Your bar must follow this requirement:
    - It must have a width equal to a fourth of tour window and have a hight about 40th of your     windows hight
    - It must be one the bottom of your window
- Now you need to be able to move your Bar

Your window with the bar should look something like this:
<----- insert imamge
And it must be movable to either side of your window

## Step 2 : I'ts brick day
Now that you have a movable bar you need some brick.
- Make 7 lines of brick with 6 brick per lines
- The line must be at the top of your window

Your Window should look like this:
<----- insert imamge

## Step 3 : A brickdown use a ball to destroy brick so make a ball
- Your ball will look like a square with the dimenssion 3/4 of the hight of your bar
- Your ball must have a fix absolute speed bettween the 2 axis
- Your ball must have collision with your bar, your brick, the side of your window and the bottom of your window
- when your ball colide a brick the brick must be destroyed

Your window should look like this:
<----- insert imamge

## Step 4 : In a real game you can loose
use this png to represented your life
<-- the png
- Now when your ball collision with the bottom of your screen you loose a life
- And When you loose all your hearth the window turn off
- When you destroy all the brick you make a win screen

You now have a game the replicate the comportement of a Brickdown



