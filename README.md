# Whitelist-Dapp

Lesson from LearnWeb3.io course in [Sophomore track](https://learnweb3.io/courses/c1d7081b-63a9-4c6e-b35c-9fcbbad418b2/lessons)
In order to run it, you need to:
1. create a .env file in the hardhat-tutorial folder and add the following lines:
```  
  QUICKNODE_HTTP_URL="add-quicknode-http-provider-url-here"
  PRIVATE_KEY="add-the-private-key-here"
```
2. Compile & deploy the smart contract from the hardhat-tutorial folder:
```
npx hardhat compile
npx hardhat run scripts/deploy.js --network goerli
```
3.Compile & run the web app from the my-app folder:
```
npm install
npm run dev
```