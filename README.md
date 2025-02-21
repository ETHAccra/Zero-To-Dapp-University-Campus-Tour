<h1>Two-Day Educational Workshop: Deploy Your Own Tokens</h1>

<p>Welcome to our <strong>Two-Day Educational Workshop</strong>! Over the next two days, you’ll learn how to create and deploy your own ERC-20 (fungible) and ERC-721 (non-fungible) tokens on the Ethereum blockchain. No prior experience is required—just bring your curiosity and enthusiasm!</p>

<hr />

<h2>Day 1: Deploying Your Own ERC-20 Token</h2>

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

<h2>Day 2: Deploying Your Own ERC-721 Token</h2>

<details>
<summary><strong>What is an ERC-721 Token?</strong></summary>
<p>ERC-721 is a standard for non-fungible tokens (NFTs) on the Ethereum blockchain. NFTs are unique and indivisible, like collectibles or digital art.</p>

<h4>Key Features of ERC-721 Tokens:</h4>
<ul>
  <li><strong>Token ID</strong>: A unique identifier for each token.</li>
  <li><strong>Owner</strong>: The address that owns a specific token.</li>
  <li><strong>Metadata</strong>: Additional information about the token (e.g., image, description).</li>
</ul>
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

<pre><code>// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

import "@openzeppelin/contracts/token/ERC721/ERC721.sol";
import "@openzeppelin/contracts/utils/Counters.sol";

contract MyNFT is ERC721 {
    using Counters for Counters.Counter;
    Counters.Counter private _tokenIds;

    constructor() ERC721("MyNFT", "MNFT") {}

    function mintNFT(address recipient, string memory tokenURI) public returns (uint256) {
        _tokenIds.increment();
        uint256 newItemId = _tokenIds.current();
        _mint(recipient, newItemId);
        _setTokenURI(newItemId, tokenURI);
        return newItemId;
    }
}</code></pre>

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

<h2>Additional Resources</h2>

<h3>Tools:</h3>
<ul>
  <li><a href="https://remix.ethereum.org/" target="_blank">Remix IDE</a>: A browser-based Solidity IDE.</li>
  <li><a href="https://metamask.io/" target="_blank">MetaMask</a>: A crypto wallet for interacting with Ethereum.</li>
  <li><a href="https://openzeppelin.com/" target="_blank">OpenZeppelin</a>: A library for secure smart contract development.</li>
</ul>

<h3>Documentation:</h3>
<ul>
  <li><a href="https://soliditylang.org/" target="_blank">Solidity Documentation</a>.</li>
  <li><a href="https://docs.openzeppelin.com/contracts/4.x/erc20" target="_blank">OpenZeppelin ERC-20 Documentation</a>.</li>
  <li><a href="https://docs.openzeppelin.com/contracts/4.x/erc721" target="_blank">OpenZeppelin ERC-721 Documentation</a>.</li>
</ul>

<hr />

<h2>Final Thoughts</h2>

<p>By the end of this two-day workshop, you’ll have deployed your own ERC-20 and ERC-721 tokens and gained hands-on experience with Ethereum development. Keep experimenting, and happy coding! 🚀</p>
