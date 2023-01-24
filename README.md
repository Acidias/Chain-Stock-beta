# Chain-Stock-beta0.5 (Ethereum TestNet)
 
This version have the responsive navbar with a Home page, Companies, Trade and Wallet Connect


Home Page:
Just basic text

Companies:
Maping trough all the companies listed in the compList.js file and listing them to the Companies homepage with basic Card styling.

Trade:
Working crypto exchange, but pairs are not set up correctly


# Update 24/01/2023
Token Balance Added Dynamically to the CompanyProfile.js
It's get the Company address form the compList.js where the I added a new key as address

# Update 20/01/2023
Worked on responsive site.

Added Transparent Background if investmodal is open

Added few extra details to Company Site


# Update 17/01/2023
Minor update, Invest PopUp windows created.


# Update 16/01/2023
Added CompanyProfile.


# Update 15/01/2023
Made Phone responsive (Sandwitch button).

Added Companies and CompanyCard.

Made multiple sides (Home, Companies, Trade).


# Update 14/01/2023
Created React (Single page, Connect Wallet, Exchange (Trade Site)).

Added Liquidity and Created the Token Pairs

Created Tokens

Created Smart Contract (CRANQ).

Start


# compList.js
example:
```js
const compList = [
    {
        name: 'Apple',
        logo: 'https://1000logos.net/wp-content/uploads/2016/10/Apple-Logo.png',
        symbol: 'AAPL',
        price: 100,
        description: 'Apple Inc. is an American multinational technology company headquartered in Cupertino, California, that designs, develops, and sells consumer electronics, computer software, and online services.',
        shares: 100,
        ceo: 'Tim Cook',
        headquarters: 'Cupertino, California, U.S.',
        founded: 'April 1, 1976; 45 years ago',
        employees: '147,000',
        sector: 'Consumer Electronics, Computer Hardware, Software, Online Services',
        address: '0x645c179Bbb630D0CAD2C18894dCE00aF3A0ab17e'
    }
]
```


