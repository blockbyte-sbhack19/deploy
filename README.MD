# URL of our working application
Our application is mobile first: iOS/Android, you need to use this public link to 

https://developer.apple.com/testflight/

# URL of our github project
https://github.com/blockbyte-sbhack19

## Backend
https://github.com/blockbyte-sbhack19/backend in branch master
Our backend is writen using corda (lender, leaser, notary) and possses mutliple endpoint
* Offer the Land: post / http://52.209.35.41:8081/api/lender/soil 
* Search the Lands: post / http://52.209.35.41:8081/api/leaser/soil/filter 
* Lease the Land: post / http://52.209.35.41:8081/api/leaser/soil 

## Frontend
* https://github.com/blockbyte-sbhack19/frontend in branch master

Our frontend use Google Flutter to offer a mobile first experience on iOS and Android (and later web and desktop as promised by Google) using one codebase.

## Parametric micro insurance product "DRY"
* https://github.com/blockbyte-sbhack19/insurance in branch master

how it is working?
it use http://www.oraclize.it/ and query data from openweatherdata every day for every parcel every day.
If for more than 30 days no rains are happening, the smart contract will pay automatically 2 ETH to all farmer that have pay a premium of 1 ETH before (today - 30 days) after 30 days pass the money will be kept by the insurer
the owner of the smart contract is the INSURER, and it collect payments from farmer

# Short description
We choose vertical 2 in agriculture

## Immutable Land Lease Ledger
Create an immutable Land Lease Ledger (LLL) where the involved parties 
can enter agreements which are fed by historic land usage data, trusted events and benefit 
from a data-driven revenue and risk sharing mechanisms.
Select your crop and the location of your field. Automated payouts are triggered by drought or flood events reported by government agencies.

