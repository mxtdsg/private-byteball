# private-byteball

- - -

## byteball-devnet
1. node version 8.11.1
2. run hub and witness

## clients side
1. node version 5.11
2. GUI wallet change node_modules/byteballcore/constants.js 
(possible bugs: # of witnesses, byteballcore version: 0.2.78 replace storage.js line75, db version) Delete the cached files in ~/.config/<app> if neccessary
3. edit `conf.js`
4. use localhost:6611 as hub
5. use another client, rename in package.json, then connect.
