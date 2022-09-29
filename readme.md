Small Guide--

How to start -

1) build project , npm install 

 if you get modules error while npm install do npm add yarn ,  yarn install  then pending dependency should install without error 


2) npm start or npm-script start 

if you see this error " Error message "error:0308010C:digital envelope routines::unsupported" " 

then run-  export NODE_OPTIONS=--openssl-legacy-provider  for ubuntu or mac

or run-  set NODE_OPTIONS=--openssl-legacy-provider   for windows 


if you have any question contact https://github.com/harjotrance  :)