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
- Create a file named "main.lua"
- Copy this little code
    ```lua
    function love.draw()
    end
    ```
- Now execute this file with the following command :
    ```sh
    > love ./
    ```

## Step 1 : First window using LOVE
---
Now that you have create your first program
