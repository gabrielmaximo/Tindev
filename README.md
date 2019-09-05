# Project: TINDEV  
#### 8º 8th edition of dev Web / Mobile workshop using the most modern tools on the market: (JavaScrip, NodeJs, ReactJs, React-Native, etc.) taught by [Diego Fernandes](https://github.com/diego3g), CTO in RocketSeat
  
## *HOW TO INSTALL TINDEV*

### Linux System Debian Base: tutorial by [tecadmin](https://tecadmin.net/install-latest-nodejs-npm-on-ubuntu/)  

  Install Curl to add nodejs in PPA:  
  ```sudo apt-get install curl```  
  
  To add PPA use the command (LTS release):  
  ```curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -```  
  
  Install node and npm with:  
  ```sudo apt-get install nodejs```  
  
  Install yarn with npm (-g for global installation):  
  ```sudo npm install yarn -g```  

### Windows System: tutorial by [nodejs.org](https://nodejs.org/en/download/package-manager/)  

  First Install Chocolatey using the powershell(ADMIN):  
  ```Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))```  

  Now install node with npm (LTS release) using the chocolatey package manager:
  ```cinst nodejs.install```  

  To complete install yarn with chocolatey:  
  ```choco install yarn```  

# Now that everything is installed globally  
run ```yarn``` command in root of the projetct to install all project dependencies of the yarn.lock.  

finally, just run the root of the backend project ```yarn dev```  
and in the root of the frontend project run ```yarn start```  

## If all dependecies is installed, the result is:  
![tindev](https://user-images.githubusercontent.com/1298871/62948028-06f81880-bdba-11e9-8046-c99bf5832e12.png)  

#### 
login with your github to access the application (mongo db limited to 5 users)
Click on the tindev icon above to log back in and register more users to view them and be able to like and match! 
![tindev](https://scontent-dfw5-1.cdninstagram.com/vp/2c3908949188f2b6636df7f48b223aaa/5DD431C4/t51.2885-15/e35/66631691_413980265887872_5438129868168162027_n.jpg?_nc_ht=scontent-dfw5-1.cdninstagram.com)  
##### obs: the match was not stylized on the frontend, I just made a visible match on the console, enjoy it!
