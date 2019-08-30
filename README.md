# OmniStack-8.0 - Projeto: TINDEV  
#### 8º Edição do workshop para dev Web/Mobile utilizando as mais modernas ferramentas de mercado: (JavaScrip, NodeJs, ReactJs, React-Native, etc..) ministrado pelo [Diego Fernandes](https://github.com/diego3g), CEO da RocketSeat
  
## Como Instalar o Tindev: // *HOW TO INSTALL TINDEV*

### Linux System Debian Base: tutorial feito por [tecadmin](https://tecadmin.net/install-latest-nodejs-npm-on-ubuntu/)  

  Install Curl to add nodejs in PPA:  
  ```sudo apt-get install curl```  
  
  To add PPA use the command (LTS release):  
  ```curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -```  
  
  Install node and npm with:  
  ```sudo apt-get install nodejs```  
  
  Install yarn with npm (-g for global installation):  
  ```sudo npm install yarn -g```  

### Windows System: tutorial feito por [nodejs.org](https://nodejs.org/en/download/package-manager/)  

  First Install Chocolatey using the powershell(ADMIN):  
  ```Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))```  

  Now install node with npm (LTS release) using the chocolatey package manager:
  ```cinst nodejs.install```  

  To complete install yarn with chocolatey:  
  ```choco install yarn```  

# Now that everything is installed globally, run the ```yarn``` command in the shell to install all project dependencies.  

finally, just run the root of the backend project ```yarn dev```  
and in the root of the frontend project run ```yarn start```  

## Se nenhum problema ocorreu até aqui, terá o seguinte resultado:  
![tindev](https://user-images.githubusercontent.com/1298871/62948028-06f81880-bdba-11e9-8046-c99bf5832e12.png)  

#### faça login com seu github, para ter acesso a base de dados, (limite de 5 usurios cadastrados, por conta do mongoDB free)   
clique no icone tindev acima para voltar ao login e cadastrar mais usurios para visualiza-los e poder curtir e dar match!  
![tindev](https://scontent-dfw5-1.cdninstagram.com/vp/2c3908949188f2b6636df7f48b223aaa/5DD431C4/t51.2885-15/e35/66631691_413980265887872_5438129868168162027_n.jpg?_nc_ht=scontent-dfw5-1.cdninstagram.com)  
##### obs: o match nao foi estilizado no frontend, fiz apenas um match visivel no console, enjoy it!
