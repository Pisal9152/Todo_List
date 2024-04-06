make sure we have installed Metamask, Ganache and Node on our computer
https://metamask.io
https://archive.trufflesuite.com/ganache
https://nodejs.org/en
open Window powershell and run command ( npm install -g truffle )
git clone these code or copy code from these directory
change directory to smart_contract by running command ( cd smart_contract )
run command ( truffle migrate ) you will see some result shown in your terminal and you have to find contract address
copy the contract address and past it into react js project
into client directory you need to go to src/App.jsx
when you are staying on App.jsx you will see
replace ( import.meta.env.VITE_CONTRACT_ADDRESS ) with the contract address you have copied from truffle migrate
change directory to client using command line ( cd client )
run command ( npm run dev )
