

# Smart Accounts creation and Social Login using Biconomy SDK 

________

A starter kit that allows you to get smart account using biconomy SDK through social login and do gasless transactions for your users using Biconomy Paymaster! 
For Demo, we are interacting with standard "counter" contract and increasing the counter value through our created smart accounts.

## Installation and Run

  npm install
  
  Once dependencies are installed, add .env file with contract address you want to interact with
  
  npm run dev
```

## Setting up Paymaster and Dashboard for your dApp :

1. Head over to the [Biconomy SDK Dashboard](https://dashboard.biconomy.io/)
2. Setup your bundlerUrl: 'https://bundler.biconomy.io/api/v2/80001/abc'
3. Get your Paymaster URL from Biconomy Dashboard . Follow the instructions on the docs [here](https://docs.biconomy.io/docs/dashboard/paymaster). It should look something like this paymasterUrl:'https://paymaster.biconomy.io/api/v1/{CHAIN_ID}/{ YOUR_API_KEY }'
   
4. Check out [Paymaster Policies](https://docs.biconomy.io/docs/dashboard/paymasterPolicies) to register your contract, load your gas tank.



## Pull requests are most welcome


