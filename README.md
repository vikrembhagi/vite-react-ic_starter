# React(Frontend) + IC Canister (Backend) Starter 

Starter src code for a react and dfinity canister deployment on the internet computer. 
Hot reloading enabled by vite. 

Src code generated from the ts-config option from repo https://github.com/MioQuispe/create-ic-app

## Requirements
- DFINITY Canister SDK
DFX_VERSION=0.7.0 sh -ci "$(curl -fsSL https://sdk.dfinity.org/install.sh)" 
- NodeJS >=16.0.0

## Get Started

`npm install`

Start the backend

`dfx start --background`

`dfx deploy`

Start the frontend

`npm run dev`
