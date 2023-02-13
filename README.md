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
- Find a way to create a rectangle and to draw it the previous window
- Your bar must follow the following requirement:
    - Height = 17
    - Width = 120
    - It must be at 64 pixel above the botom of your window
    - It must be centered
- The bar must be movable by the user using the array of your keyboard, the bar should move all the way to the left or the right of the window

Your window with the bar should look something like this:
![image](https://user-images.githubusercontent.com/72023610/218500790-a6ce6be9-3d5b-4577-af3f-a77b2d28a1c0.png)


## Step 2 : I'ts brick day
Now that you have a movable bar you need some brick.
- Make 7 lines of brick with 6 brick per lines
- A brick is 75 width, 18 height 
- The line first line must be separate by from the top of the window by 5

Your Window should look like this:
<----- insert imamge

## Step 3 : A Brickbreacker use a ball to destroy brick so make a ball
- Your ball will look like a square with a side of 14
- Your ball must have a fix absolute speed bettween the 2 axis
- Your ball must colide with your bar, your brick, the side of your window and the bottom of your window
- when the ball colide with a brick, the brick must be destroyed

Your window should look like this:
<----- insert imamge

## Step 4 : In a real game you can loose
use this png to represented your life
<-- the png
- Put 3 hearth on the botom left of the window
- Now when your ball collision with the bottom of your screen one of your hearth disapere
- And When you loose all your hearth draw a loose screen
- When you destroy all the brick you draw a win screen

You now have a game the replicate the comportement of a Brickdown



