# midwayBarbershop
Mobile app for Midway Barbershop

## Install process
1. Install NPM (node package manager) onto your machine. 
2. Install angular cli globally:  `npm i @angular/cli`
3. Install ionic globally: `npm install -g ionic`
4. Clone Repository:  `git clone https://github.com/kwb5105/midwayBarbershop.git`
5. cd into new repository location: `cd midwayBarbershop`
6. serve the application: `ionic serve`


## Code Push/Build process
1. Run the Ionic build process: `ionic build`
(This will generate the www file that will be used to deploy the code on the server)
2. `git add .`
3. `git commit -m"<Message here>"`
4. `git push`

- Best to deploy to own branch, then generate a pull request to merge to master branch

## Server code deployment process
1. Log into application server: `http://54.89.234.118`
2. navigate to the midway barbershop folder. `cd /midwayBarbershop/www`
3. pull latest code: `git pull`
4. restart nginx: `systemctl restart nginx`
