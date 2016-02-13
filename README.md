# sssetup
quick setup of ss server
## set up your server
`git clone git@github.com:shrik3/sssetup.git`
`cd sssetup`
`./setup`

## start the server

There are many way to start the server

### You can simply use the command 
`nohup /usr/local/bin/ss-server -s [server ip] -p [server port] -k [password] -m [method] &`

###or use the 'start' script
1.`vi start` add modify the scriptn and save 
2. `./start`

## make sure the port you use is allowed by your firewall

