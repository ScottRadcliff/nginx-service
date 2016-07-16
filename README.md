# Nginx Service Script
This is the script for setting up service scripts for nginx. When I install via passenger, I don't get these and always have to manually start/restart nginx. I also have this listed as a [gist](https://gist.github.com/ScottRadcliff/d4cc014b587489650d991af7a1c6c5fa), but I'm worried that someday that file that I download may be gone.

To get this working, paste the contents of the `nginx` file into `/etc/init.d/nginx` and chmod it `sudo chmod +x /etc/init.d/nginx`

Now you get:  

`sudo service nginx stop`  
`sudo service nginx start`  
`sudo service nginx restart`  
`sudo service nginx reload`  
