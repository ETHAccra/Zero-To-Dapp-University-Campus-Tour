<div align="center" ><img width="350px" src="https://github.com/ETHAccra/Zero-To-Dapp-University-Campus-Tour/blob/main/ETHAccra-LogoFiles_PrimaryBadge.png"></div>

<h2>Additional Resources</h2>
<h3>Useful Links:</h3>
<ul>
  <li><a href="https://cloud.google.com/application/web3/faucet/ethereum/sepolia" target="_blank">Ethereum Sepolia Faucet</a></li><br>

  Excel Sheet

https://docs.google.com/spreadsheets/d/1ZAkXVR__H807meA7yBuMVyklFv04hQ4ZhubhgpgWyCA/edit?usp=sharing

</ul>
<h3>Presentation:</h3>
<ul>
  <li><a href="https://docs.google.com/presentation/d/1GsH-hoath5B_ua9r4xmvySFhFWy9rOBe/edit?usp=sharing&ouid=109207709370381780005&rtpof=true&sd=true" target="_blank">ETHAccra Presentation</a></li>
  <li><a href="https://docs.google.com/presentation/d/1UkdDAZYwNiS0rGIkdulOonFH6FDs4z9smaaj5iDim1s/edit#slide=id.g12e1023695a_0_0" target="_blank">Remix IDE Presentation</a></li>
  <li><a href="https://docs.google.com/presentation/d/1k1KdmTqtT6bBCXgeMVXWxD0qcWU2VEHHZFb5T5iFs-A/edit?usp=sharing" target="_blank">The Graph Presentation</a></li>

In Solidity, events are a way to log and notify external entities (such as user interfaces or other smart contracts) about specific occurrences within a smart contract.

Indexing refers to a data structure that allows for faster retrieval of data by creating pointers to the location of data within a table.

</ul>

<h3>Tools:</h3>
<ul>
  <li><a href="https://remix.ethereum.org/" target="_blank">Remix IDE</a>: A browser-based Solidity IDE.</li>
  <li><a href="https://metamask.io/" target="_blank">MetaMask</a>: A crypto wallet for interacting with Ethereum.</li>
  <li><a href="https://openzeppelin.com/" target="_blank">OpenZeppelin</a>: A library for secure smart contract development.</li>
</ul>

<h1>Introduction to Ethereum Development: Key Terms and Concepts</h1>

<p>Welcome to the world of Ethereum development! This guide will introduce you to the essential terms and concepts you need to know as a beginner blockchain developer. By the end of this guide, you’ll have a solid understanding of blockchain fundamentals and Ethereum-specific concepts.</p>

<hr />

<h2>What is Blockchain?</h2>

<details>
<summary><strong>Definition</strong></summary>
<p>A blockchain is a decentralized, distributed ledger that records transactions across a network of computers. Each block contains a list of transactions, and these blocks are linked together in a chain, hence the name "blockchain."</p>
</details>

<details>
<summary><strong>Key Features</strong></summary>
<ul>
  <li><strong>Decentralization</strong>: No single entity controls the network.</li>
  <li><strong>Transparency</strong>: All transactions are visible to everyone on the network.</li>
  <li><strong>Immutability</strong>: Once data is recorded, it cannot be altered.</li>
</ul>
</details>

<hr />

<h2>What is Ethereum?</h2>

<details>
<summary><strong>Definition</strong></summary>
<p>Ethereum is a decentralized, open-source blockchain platform that enables developers to build and deploy smart contracts and decentralized applications (dApps). Unlike Bitcoin, which is primarily a digital currency, Ethereum is a programmable blockchain.</p>
</details>

<details>
<summary><strong>Key Features</strong></summary>
<ul>
  <li><strong>Smart Contracts</strong>: Self-executing contracts with the terms of the agreement written in code.</li>
  <li><strong>Ether (ETH)</strong>: The native cryptocurrency of the Ethereum network, used to pay for transactions and computational services.</li>
  <li><strong>Decentralized Applications (dApps)</strong>: Applications that run on the Ethereum blockchain.</li>
</ul>
</details>

<hr />

<h2>Key Blockchain Terms</h2>

<details>
<summary><strong>Node</strong></summary>
<p>A computer that participates in the blockchain network by validating and relaying transactions. Nodes maintain a copy of the blockchain and ensure its integrity.</p>
</details>

<details>
<summary><strong>Consensus Mechanism</strong></summary>
<p>A method used to achieve agreement on the state of the blockchain across all nodes. Common consensus mechanisms include Proof of Work (PoW) and Proof of Stake (PoS).</p>
</details>

<details>
<summary><strong>Gas</strong></summary>
<p>A unit of measurement for the computational effort required to execute operations on the Ethereum network. Gas fees are paid in Ether (ETH) and compensate miners (or validators) for their work.</p>
</details>

<details>
<summary><strong>Wallet</strong></summary>
<p>A software application that allows users to interact with the blockchain. Wallets store private keys, which are used to sign transactions and prove ownership of assets.</p>
</details>

<hr />

<h2>Consensus Mechanisms</h2>

<details>
<summary><strong>Proof of Work (PoW)</strong></summary>
<p>PoW is a consensus mechanism where miners solve complex mathematical puzzles to validate transactions and create new blocks. The first miner to solve the puzzle gets to add the block to the blockchain and is rewarded with cryptocurrency.</p>

<h4>Pros:</h4>
<ul>
  <li>High security due to computational difficulty.</li>
</ul>

<h4>Cons:</h4>
<ul>
  <li>Energy-intensive and environmentally unfriendly.</li>
</ul>
</details>

<details>
<summary><strong>Proof of Stake (PoS)</strong></summary>
<p>PoS is a consensus mechanism where validators are chosen to create new blocks based on the number of tokens they hold and are willing to "stake" as collateral. Validators are rewarded with transaction fees.</p>

<h4>Pros:</h4>
<ul>
  <li>Energy-efficient compared to PoW.</li>
</ul>

<h4>Cons:</h4>
<ul>
  <li>Wealth concentration can lead to centralization.</li>
</ul>
</details>

<details>
<summary><strong>Delegated Proof of Stake (DPoS)</strong></summary>
<p>DPoS is a variation of PoS where token holders vote for a small number of delegates to validate transactions and create blocks on their behalf.</p>

<h4>Pros:</h4>
<ul>
  <li>Faster transaction processing.</li>
</ul>

<h4>Cons:</h4>
<ul>
  <li>Potential for centralization if delegates collude.</li>
</ul>
</details>

<hr />

<h2>Smart Contracts</h2>

<details>
<summary><strong>Definition</strong></summary>
<p>Smart contracts are self-executing contracts with the terms of the agreement directly written into code. They automatically execute and enforce the terms when predefined conditions are met.</p>
</details>

<details>
<summary><strong>Use Cases</strong></summary>
<ul>
  <li>Decentralized Finance (DeFi): Lending, borrowing, and trading without intermediaries.</li>
  <li>Supply Chain Management: Tracking goods and ensuring transparency.</li>
  <li>Digital Identity: Verifying identity without centralized authorities.</li>
</ul>
</details>

<hr />
<h2>Introduction To Solidity</h2>
<details>
<summary><strong> Solidity Fundamentals</strong></summary><br>



### Topics To be Covered:
- Basic syntax and structure of a Solidity contract.
- Data types: `uint`, `address`, `bool`, `string`, etc.
- Variables: State variables, local variables, and constants.
- Functions: Visibility (`public`, `private`, `internal`, `external`), and modifiers.

<h2>1. Basic Structure of a Solidity Contract</h2>
<p>A Solidity smart contract starts with the <code>pragma</code> directive, followed by the contract definition. Solidity contracts contain functions, variables, and logic that define how they interact on the blockchain.</p>
<pre><code>
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.19; // Specifies the Solidity version

contract MyFirstContract {
    // Contract content goes here
}
</code></pre>

<h2>2. Data Types in Solidity</h2>
<h3>Value Types</h3>
<ul>
    <li><strong>Boolean (<code>bool</code>)</strong>: Stores <code>true</code> or <code>false</code>.</li>
    <li><strong>Unsigned Integer (<code>uint</code>)</strong>: Represents non-negative integers.</li>
    <li><strong>Signed Integer (<code>int</code>)</strong>: Stores positive and negative integers.</li>
    <li><strong>Address (<code>address</code>)</strong>: Stores Ethereum addresses.</li>
    <li><strong>Bytes (<code>bytes1</code> to <code>bytes32</code>)</strong>: Used for cryptographic operations.</li>
    <li><strong>String (<code>string</code>)</strong>: Used for storing text.</li>
</ul>

<h2>3. Functions in Solidity</h2>

***Basic Structure Of A function***<br>
<img src="https://github.com/eben619/Celo_Africa_Dao-Ghana_University_Tour/blob/main/function.avif" width="500px"><br>

<p>Functions define the behavior of a smart contract. They can be public, private, view (read-only), or payable (can receive Ether).</p>
<pre><code>
function getName() public pure returns (string memory) {
    return "KNUST_Tour"; // Returns a fixed string
}
</code></pre>

<h2>4. Variables in Solidity</h2>

<h3>State Variables</h3>
<p>State variables are permanently stored on the blockchain. They retain their values even after the contract execution ends.</p>
<pre><code>
contract Example {
    uint256 public storedNumber; // A state variable stored on the blockchain
    function setNumber(uint256 _num) public {
        storedNumber = _num; // Updates the state variable
    }
}
</code></pre>

<h3>Local Variables</h3>
<p>Local variables exist only within a function's execution scope. They do not persist on the blockchain.</p>
<pre><code>
function getNumber() public pure returns (uint256) {
    uint256 localNumber = 10; // Local variable, exists only in this function
    return localNumber;
}
</code></pre>

<h3>Global Variables</h3>
<p>Global variables provide blockchain-related information such as the sender's address, block number, or timestamp.</p>
<pre><code>
uint256 public blockNumber = block.number; // Gets the current block number
address public sender = msg.sender; // Gets the address of the sender
</code></pre>

<h2>5. Control Structures (If-Else, Loops)</h2>

<h3>If-Else Statement</h3>
<p>The if-else statement allows conditional execution of code based on specific conditions.</p>
<pre><code>
function checkEven(uint256 num) public pure returns (string memory) {
    if (num % 2 == 0) {
        return "Even"; // Returns "Even" if the number is divisible by 2
    } else {
        return "Odd"; // Returns "Odd" if the number is not divisible by 2
    }
}
</code></pre>

<h2>6. Mappings and Structs</h2>

<h3>Mappings</h3>
<p>Mappings store key-value pairs, where keys are unique, and values can be of any type.</p>
<pre><code>
mapping(address => uint256) public balances; // Maps addresses to balances

function updateBalance(address _user, uint256 _amount) public {
    balances[_user] = _amount; // Updates the balance for the user
}
</code></pre>

<h3>Structs</h3>
<p>Structs are used to define custom data structures, grouping multiple data fields.</p>
<pre><code>
struct Student {
    string name;
    uint256 age;
}

Student public student; // Declares a student struct variable

function setStudent(string memory _name, uint256 _age) public {
    student = Student(_name, _age); // Assigns values to the student struct
}
</code></pre>

<h2>7. Events and Logging</h2>
<p>Events in Solidity allow logging data on the blockchain. They are mainly used to track actions like transactions or contract updates.</p>
<pre><code>
event UserRegistered(address indexed user, uint256 timestamp); // Declares an event

function registerUser() public {
    emit UserRegistered(msg.sender, block.timestamp); // Emits an event when a user registers
}
</code></pre>

<h2>8. Modifiers</h2>
<p>Modifiers define rules that must be met before executing a function. They help enforce access control and conditions.</p>
<pre><code>
modifier onlyOwner() {
    require(msg.sender == owner, "Not the owner"); // Checks if the caller is the contract owner
    _;
}

function restrictedFunction() public onlyOwner {
    // Function logic that only the owner can execute
}
</code></pre>

<h2>9. Payable Functions (Handling Ether)</h2>
<p>Payable functions allow contracts to receive and send Ether. The <code>msg.value</code> property holds the amount of Ether sent.</p>
<pre><code>
function deposit() public payable {
    require(msg.value > 0, "Must send some Ether"); // Ensures Ether is sent
}

function getBalance() public view returns (uint256) {
    return address(this).balance; // Returns the contract's balance
}
</code></pre>

### Materials:
- **Book**: *Mastering Ethereum* (Chapter 7: Smart Contracts and Solidity).

</details>

<h2>Decentralized Applications (dApps)</h2>

<details>
<summary><strong>Definition</strong></summary>
<p>dApps are applications that run on a blockchain network rather than a centralized server. They leverage smart contracts for their backend logic and often have a frontend user interface.</p>
</details>

<details>
<summary><strong>Examples</strong></summary>
<ul>
  <li><strong>Uniswap</strong>: A decentralized exchange for trading tokens.</li>
  <li><strong>CryptoKitties</strong>: A game where users can collect and breed digital cats.</li>
  <li><strong>Compound</strong>: A DeFi platform for lending and borrowing cryptocurrencies.</li>
</ul>
</details>

<hr />

<h2>Campus Tour Workshop: Deploy Your Own Tokens</h2>

<hr />

<h2> Deploying Your Own ERC-20 Token</h2>

<details>
<summary><strong>What is an ERC-20 Token?</strong></summary>
<p>ERC-20 is a standard for fungible tokens on the Ethereum blockchain. Fungible tokens are interchangeable, like currencies (e.g., 1 ETH = 1 ETH).</p>

<h4>Key Features of ERC-20 Tokens:</h4>
<ul>
  <li><strong>Total Supply</strong>: The total number of tokens in circulation.</li>
  <li><strong>Balance</strong>: The number of tokens held by an address.</li>
  <li><strong>Transfer</strong>: Sending tokens from one address to another.</li>
  <li><strong>Approve and TransferFrom</strong>: Allowing third parties to transfer tokens on your behalf.</li>
</ul>
</details>

<details>
<summary><strong>Step 1: Set Up Your Environment</strong></summary>
<ol>
  <li>Open <a href="https://remix.ethereum.org/" target="_blank">Remix IDE</a>, a browser-based Solidity IDE.</li>
  <li>Connect your <a href="https://metamask.io/" target="_blank">MetaMask</a> wallet to Remix.</li>
  <li>Ensure MetaMask is connected to a testnet like Ropsten or Rinkeby.</li>
</ol>
</details>

<details>
<summary><strong>Step 2: Write the ERC-20 Contract</strong></summary>
<p>Here’s a simple ERC-20 token contract using OpenZeppelin’s library:</p>

<pre><code>// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";

contract MyToken is ERC20 {
    constructor(uint256 initialSupply) ERC20("MyToken", "MTK") {
        _mint(msg.sender, initialSupply);
    }
}</code></pre>

<h4>Explanation:</h4>
<ul>
  <li><strong><code>ERC20("MyToken", "MTK")</code></strong>: Creates a token with the name "MyToken" and symbol "MTK".</li>
  <li><strong><code>_mint(msg.sender, initialSupply)</code></strong>: Mints the initial supply of tokens to the deployer's address.</li>
</ul>
</details>

<details>
<summary><strong>Step 3: Compile and Deploy</strong></summary>
<ol>
  <li>Compile the contract in Remix.</li>
  <li>Deploy the contract to the testnet using MetaMask.</li>
  <li>Confirm the transaction in MetaMask.</li>
</ol>
</details>

<details>
<summary><strong>Step 4: Interact with Your ERC-20 Token</strong></summary>
<ol>
  <li><strong>Check Your Balance</strong>: Use the <code>balanceOf</code> function in Remix to check your token balance.</li>
  <li><strong>Transfer Tokens</strong>: Use the <code>transfer</code> function to send tokens to another address.</li>
  <li><strong>Approve and TransferFrom</strong>: Use <code>approve</code> to allow another address to spend your tokens, then use <code>transferFrom</code> to transfer tokens on their behalf.</li>
</ol>
</details>

<hr />

<details>
  <summary><h1>CryptoPunks Subgraph Deployment</h1></summary>

  <h2>1. Install The Graph CLI</h2>
  <p>Ensure you have <a href="https://thegraph.com/docs/en/developing/quick-start/">The Graph CLI</a> installed:</p>
  <pre>
  npm install -g @graphprotocol/graph-cli
  </pre>

  <h2>2. Initialize Your Subgraph</h2>
  <p>Run the following command to create a new subgraph:</p>
  <pre>
  graph init --product hosted-service crypto-punks-subgraph --from-contract 0xb47e3cd837dDF8e4c57F05d70Ab865de6e193BBB --network mainnet
  </pre>

  <p>Folder structure:</p>
  <pre>
  crypto-punks-subgraph/
  │── abis/
  │   ├── CryptoPunks.json
  │── src/
  │   ├── cryptoPunks.ts
  │── schema.graphql
  │── subgraph.yaml
  </pre>

  <h2>3. Update <code>subgraph.yaml</code></h2>
  <p>Edit the <code>subgraph.yaml</code> file:</p>
  <pre>
  specVersion: 0.0.5
  description: A subgraph to index CryptoPunks on Ethereum mainnet
  schema:
    file: ./schema.graphql
  dataSources:
    - kind: ethereum
      name: CryptoPunks
      network: mainnet
      source:
        address: "0xb47e3cd837dDF8e4c57F05d70Ab865de6e193BBB"
        abi: CryptoPunks
        startBlock: 3914495
      mapping:
        kind: ethereum/events
        apiVersion: 0.0.7
        language: wasm/assemblyscript
        entities:
          - Transfer
          - CryptoPunk
        abis:
          - name: CryptoPunks
            file: ./abis/CryptoPunks.json
        eventHandlers:
          - event: PunkTransfer(indexed address,indexed address,indexed uint256)
            handler: handlePunkTransfer
          - event: PunkBought(indexed uint256,indexed uint256,indexed address)
            handler: handlePunkBought
        file: ./src/cryptoPunks.ts
  </pre>

  <h2>4. Define the Schema (<code>schema.graphql</code>)</h2>
  <p>This defines the indexed data structure:</p>
  <pre>
  type Transfer @entity(immutable: true) {
    id: Bytes!
    from: Bytes!
    to: Bytes!
    tokenId: BigInt! 
    blockNumber: BigInt!
    transactionHash: Bytes!
  }

  type CryptoPunk @entity {
    id: ID!
    owner: Bytes!
    punkIndex: BigInt!
    blockNumber: BigInt!
  }

  type PunkSale @entity {
    id: ID!
    buyer: Bytes!
    punkIndex: BigInt!
    amount: BigInt!
    blockNumber: BigInt!
  }
  </pre>

  <h2>5. Event Handlers (<code>src/cryptoPunks.ts</code>)</h2>
  <p>Implement event handlers in AssemblyScript:</p>
  <pre>
  import {
    PunkTransfer as PunkTransferEvent,
    PunkBought as PunkBoughtEvent,
  } from "../generated/CryptoPunks/CryptoPunks"
  import {
    CryptoPunk,
    Transfer,
    PunkSale
  } from "../generated/schema"

  export function handlePunkTransfer(event: PunkTransferEvent): void {
    let transfer = new Transfer(event.transaction.hash.concatI32(event.logIndex.toI32()))
    transfer.from = event.params.from
    transfer.to = event.params.to
    transfer.tokenId = event.params.tokenIndex
    transfer.blockNumber = event.block.number
    transfer.transactionHash = event.transaction.hash
    transfer.save()

    let punk = CryptoPunk.load(event.params.tokenIndex.toString());
    if (punk == null) {
      punk = new CryptoPunk(event.params.tokenIndex.toString());
    }
    punk.owner = event.params.to;
    punk.punkIndex = event.params.tokenIndex;
    punk.blockNumber = event.block.number;
    punk.save();
  }

  export function handlePunkBought(event: PunkBoughtEvent): void {
    let sale = new PunkSale(event.transaction.hash.concatI32(event.logIndex.toI32()));
    sale.buyer = event.params.to;
    sale.punkIndex = event.params.tokenIndex;
    sale.amount = event.params.amount;
    sale.blockNumber = event.block.number;
    sale.save();
  }
  </pre>

  <h2>6. Create ABI File (<code>abis/CryptoPunks.json</code>)</h2>
  <p>Get the CryptoPunks ABI from <a href="https://etherscan.io/address/0xb47e3cd837dDF8e4c57F05d70Ab865de6e193BBB#code">Etherscan</a> and save it as <code>abis/CryptoPunks.json</code>.</p>

  <h2>7. Deploy the Subgraph</h2>
  <p>Run the following commands:</p>
  <pre>
  graph auth --product hosted-service &lt;DEPLOY_KEY&gt;
  graph codegen
  graph build
  graph deploy --product hosted-service &lt;GITHUB_USERNAME&gt;/crypto-punks-subgraph
  </pre>

  <p>Replace <code>&lt;DEPLOY_KEY&gt;</code> with your The Graph API key and <code>&lt;GITHUB_USERNAME&gt;</code> with your GitHub username.</p>

  <h2>8. Query Data</h2>
  <p>Use the GraphQL Playground to fetch indexed CryptoPunks:</p>
  <pre>
  {
    transfers(where: {tokenId: "999"}, orderBy: blockNumber, orderDirection: asc) {
      id
      tokenId
      from
      to
      blockNumber
    }
    cryptoPunks(where: {id: "999"}) {
      id
      owner
      punkIndex
      blockNumber
    }
    punkSales(where: {punkIndex: "999"}) {
      id
      buyer
      amount
      blockNumber
    }
  }
  </pre>

  <h2>Conclusion</h2>
  <p>This setup allows you to track CryptoPunks ownership transfers, sales, and metadata efficiently using The Graph. 🚀</p>

</details>


<h2> Deploying Your Own ERC-721 Token</h2>

<details>
<summary><strong>What is an ERC-721 Token?</strong></summary>
<p>ERC-721 is a standard for non-fungible tokens (NFTs) on the Ethereum blockchain. NFTs are unique and indivisible, like collectibles or digital art.</p>

<h4>Key Features of ERC-721 Tokens:</h4>
<ul>
  <li><strong>Token ID</strong>: A unique identifier for each token.</li>
  <li><strong>Owner</strong>: The address that owns a specific token.</li>
  <li><strong>Metadata</strong>: Additional information about the token (e.g., image, description).</li>
</ul>

Storage of your NFT metadata and art file. 

https://pinata.cloud/

Generating your metadata (json) file

https://app.imintify.com/metadata

</details>

<details>
<summary><strong>Step 1: Set Up Your Environment</strong></summary>
<ol>
  <li>Open <a href="https://remix.ethereum.org/" target="_blank">Remix IDE</a>.</li>
  <li>Connect your <a href="https://metamask.io/" target="_blank">MetaMask</a> wallet to Remix.</li>
  <li>Ensure MetaMask is connected to a testnet like Ropsten or Rinkeby.</li>
</ol>
</details>

<details>
<summary><strong>Step 2: Write the ERC-721 Contract</strong></summary>
<p>Here’s a simple ERC-721 token contract using OpenZeppelin’s library:</p>

<pre><code>

  // SPDX-License-Identifier: MIT
// Compatible with OpenZeppelin Contracts ^5.0.0
pragma solidity ^0.8.22;

import {ERC721} from "@openzeppelin/contracts/token/ERC721/ERC721.sol";
import {ERC721URIStorage} from "@openzeppelin/contracts/token/ERC721/extensions/ERC721URIStorage.sol";
import {Ownable} from "@openzeppelin/contracts/access/Ownable.sol";

contract MyToken is ERC721, ERC721URIStorage, Ownable {
    constructor(address initialOwner)
        ERC721("MyToken", "MTK")
        Ownable(initialOwner)
    {}

    function safeMint(address to, uint256 tokenId, string memory tokenURI_) public onlyOwner {
        _safeMint(to, tokenId);
        _setTokenURI(tokenId, tokenURI_);  // Assign the specific URI
    }

    // Overrides required by Solidity
    function tokenURI(uint256 tokenId)
        public
        view
        override(ERC721, ERC721URIStorage)
        returns (string memory)
    {
        return super.tokenURI(tokenId);
    }

    function supportsInterface(bytes4 interfaceId)
        public
        view
        override(ERC721, ERC721URIStorage)
        returns (bool)
    {
        return super.supportsInterface(interfaceId);
    }
}

</code></pre>

<h4>Explanation:</h4>
<ul>
  <li><strong><code>ERC721("MyNFT", "MNFT")</code></strong>: Creates an NFT collection with the name "MyNFT" and symbol "MNFT".</li>
  <li><strong><code>mintNFT</code></strong>: Mints a new NFT and assigns it to the recipient with a unique token ID and metadata URI.</li>
</ul>
</details>

<details>
<summary><strong>Step 3: Compile and Deploy</strong></summary>
<ol>
  <li>Compile the contract in Remix.</li>
  <li>Deploy the contract to the testnet using MetaMask.</li>
  <li>Confirm the transaction in MetaMask.</li>
</ol>
</details>

<details>
<summary><strong>Step 4: Interact with Your ERC-721 Token</strong></summary>
<ol>
  <li><strong>Mint Your First NFT</strong>: Call the <code>mintNFT</code> function with your address and a metadata URI (e.g., an IPFS link).</li>
  <li><strong>Check Ownership</strong>: Use the <code>ownerOf</code> function in Remix to check who owns a specific token.</li>
  <li><strong>Transfer NFTs</strong>: Use the <code>transferFrom</code> function to send an NFT to another address.</li>
</ol>
</details>

<hr />

<h3>Documentation:</h3>
<ul>
  <li><a href="https://soliditylang.org/" target="_blank">Solidity Documentation</a>.</li>
  <li><a href="https://docs.openzeppelin.com/contracts/4.x/erc20" target="_blank">OpenZeppelin ERC-20 Documentation</a>.</li>
  <li><a href="https://docs.openzeppelin.com/contracts/4.x/erc721" target="_blank">OpenZeppelin ERC-721 Documentation</a>.</li>
</ul>

<hr />

<h2>Final Thoughts</h2>

<p>By the end of this two-day workshop, you’ll have deployed your own ERC-20 and ERC-721 tokens and gained hands-on experience with Ethereum development. Keep experimenting, and happy coding! 🚀</p>
