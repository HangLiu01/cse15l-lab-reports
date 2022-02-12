# **_LAB REPORT 3_**
# **Streamlining SSH configuration

Streamlining SSH configuration is a easier and more convenient way to connect remote server. 

First, we need to find/add configuration file in your computer's ssh folder. 

Go to your computer's bash or terminal and type
> _`cd .ssh`_

Find your config file. If not, create one and type: 
> ![Image](code1.png)
_Tips: you can change the name after Host to name whatever you like._

Now, you are able to log on the remote code with a simplier command: 
> ![Image](code2.png)

Lastly, lets try to use the host name we create to move some files!
Try: 
> `scp (your filename) (host name)`

This is the example I have: 
> ![Iamge](code3.png)



