<p>Hardhat Installation</p>
<ul>
    <li>
        <h3>Step 1: Type "npm init --yes"</h3>
    </li>
    <li>
        <h3>Step 2: Type "npm install --save-dev hardhat"</h3>
    </li>
    <li>
        <h3>Step 1: Type "npx hardhat" and select "empty hardhat.config.js"</h3>
    </li>
</ul>

<p>Compilation using Hardhat</p>
<ul>
    <li>
        <h3>Step 1: Create folders named as contracts, scripts and test. Create a contract named "Token.sol" and write a contract to create a token.</h3>
    </li>
    <li>
        <h3>Step 2: Go to terminal and move to contracts folder using "cd contracts" command and type "npx hardhat compile".</h3>
    </li>
</ul>

<p>Testing using Hardhat</p>
<ul>
    <li>
        <h3>Step 1: Before starting install few packages.</h3>
        <p>"npm install --save-dev @nomiclabs/hardhat-ethers ethers @nomiclabs/hardhat-waffle ethereum-waffle chai"</p>
    </li>
    <li>
        <h3>Step 2: Create a file inside test folder, "token.js" and write the testing script.</h3>
    </li>
    <li>
        <h3>Step 3: Type "npx hardhat test"</h3>
    </li>
</ul>

<p>Debugging using Hardhat</p>
<ul>
    <li>
        <h3>Step 1: Import console package for solidity into the smart contract.</h3>
    </li>
    <li>
        <h3>Step 2: Write the debugging script into the smart contract.</h3>
    </li>
    <li>
        <h3>Step 3: Type "npx hardhat test"</h3>
    </li>
</ul>

<p>Deploying on live test network using Hardhat</p>
<ul>
    <li>
        <h3>Step 1: Go to Hardhat config file and add the http link and private key for the test network using Alchemy.</h3>
    </li>
    <li>
        <h3>Step 2: Type "npx hardhat run scripts/deploy.js --network sepolia".</h3>
    </li>
</ul>

<p>Contract Address (Sepolia Test network): 0x2d722505CD800fe93cAE8E67f5F070856EA9a354</p>