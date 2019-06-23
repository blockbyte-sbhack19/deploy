# Short description
We choose vertical 2 in agriculture

## Immutable Land Lease Ledger
Create an immutable Land Lease Ledger (LLL) where the involved parties 
can enter agreements which are fed by historic land usage data, trusted events and benefit 
from a data-driven revenue and risk sharing mechanisms.
Select your crop and the location of your field. Automated payouts are triggered by drought or flood events reported by government agencies.

# URL of our working application
Our application is mobile first: iOS/Android v1.0.2, to see it live you need 
* Install TestFlight (https://developer.apple.com/testflight/) from App store on your iPhone 
* Send an email to our team lead with your appleId 
* You receive an email from Apple saying "You're invited to join a development team." click in email link and follow instructions (you're now part of the organization Blockbyte ;-))
* Send an email to our team lead, that you accepted the invitation
* You receive another email with subject "BlockByte has invited you to test Lend It!."
* Open the TestFlight app and install Lend-It
* Happy testing :)

# URL of our github project
https://github.com/blockbyte-sbhack19

## Frontend
* https://github.com/blockbyte-sbhack19/frontend in branch master
* https://github.com/blockbyte-sbhack19/frontend-design/ in branch master

Our frontend use Google Flutter to offer a mobile first experience on iOS and Android (and later web and desktop as promised by Google) using one codebase.

## Backend
https://github.com/blockbyte-sbhack19/backend in branch master

Our backend is writen using Corda (lender, leaser, notary) and posseses mutliple web endpoints

## Parametric micro insurance product "DRY"
* https://github.com/blockbyte-sbhack19/insurance in branch master

it use http://www.oraclize.it/ and query data from openweatherdata every day for every parcel (lat, long).
If for more than 30 days it is not raining, the smart contract will pay automatically 2 ETH to all farmer that have pay a premium of 1 ETH before (today - 30 days) after 60 days pass the money will be kept by the insurer
the owner of the smart contract is the INSURER, and it collect payments from farmers



