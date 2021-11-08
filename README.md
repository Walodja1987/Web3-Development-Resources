# Web3 Development Resources

This is a curated list of web3 related tutorials that I personally found very helpful when starting with web3 development. When I started, I had several years of programming experience in Matlab, Python, Excel VBA, and SQL but no meaningful experience in web2 development. As web3 builds on top of web2, you will also find web2 content which I had to learn as well. Feel free to ignore if you know it already.

# 💎Solidity
* [Full Solidity course by Stephen Grider][Grider] - Excellent udemy course that teaches you the basics of interacting with smart contracts on Ethereum without using a framework like truffle or hardhat. This will help you to appreciate truffle/hardhat later on. Note that this tutorial uses an old version of the Solidity compiler, but I think it's still worth it as he explains the general concepts very well.
* [Eattheblocks tutorials on youtube][Eattheblocks] - Eattheblocks has many short tutorials and intros on Solidity and Web3 which I found very helpful.

# 🎭 NFT minting
* [Alchemy NFT minting tutorial][AlchemyNFT] - Great tutorial showing how to set up an NFT minting page starting from the Solidity contracts in hardhat and then implementing the Wallet Connect button and the mint functionality using React. Highly recommended! 

# 🕸️ React
* [How to build a website in React][ReactWebsite] - Great tutorial to learn how to build a website using a React (web2)  
* [Task tracker][TaskTrackerReact] - Great tutorial to learn how to build an interactive task tracker in React (web2)

# 🎨 CSS
* [Complete Course][CSSCompleteCourse] - Very good full course on CSS. 

# 📜 Typescript
* [Typescript Crash Course] - Typescript is an open source programming language that builds on JavaScript and offers additional features. It helps to know what it is as it's used in several web3 projects (e.g., 0x protocol). It’s often referred to as the superset of JavaScript, i.e. it’s JavaScript plus some additional features.

# 💻 Developer stack
## IDE
* [Visual Studio Code][VSCode] - Preferred IDE for web3 development (Solidity, React, etc.). See section below on useful VSCode extensions
* [Remix] - Online IDE for quick Smart Contract prototyping and testing
## Smart contract development
* [Hardhat] - Popular smart contract development framework. Considered superior to Truffle by many developers (incl. myself). 
* [Truffle] - Alternative to hardhat. Good to know about as many tutorials are still based on it but developers started to prefer hardhat recently. 
* [Web3 library] - A JavaScript library to interact with Ethereum (I personally prefer web3 over etherjs as the documentation is easier to understand).
* [Etherjs] - Alternative to Web3. Hardhat's recommended choice to interact with Ethereum.
## Testing
* [Mocha] - Test framework that runs your tests, as defined with <code>describe</code>, <code>it</code>, etc.
* [Chai] - Chai asserts that the values in your tests are correct (<code>expect</code>, <code>assert</code>)
* [Waffle] - Test framework for writing and testing smart contracts. It provides tools for compiling and deploying contracts, functions for testing contracts, contract mocks, extra Chai assertions etc. It can be used in addition to Mocha (as well as other test runners like Jest), Waffle does not run tests itself. Waffle is [hardhat's recommended choice] for testing.


# Useful VSCode extensions
* ES7 React/Redux/GraphQL/React-Native snippets by dsznajder
* JSON formatter by Clemens Peters
* Live Server by Ritwick Dey
* soliditiy by Juan Blanco

# Cheat sheets
... in the making ...

# Contribution

Rather than sharing general links to webpages, my goal is to maintain a short list of helpful tutorials that cover most of the relevant topics that a web3 developer needs to know. You can contribute as follows:
* **Add new tutorials**: If you want to add to this list, open an issue, share the link, describe what the tutorial is about and why you like it. 
* **Edit existing list**: If you believe that there are better tutorials/packages/tools than the ones that I listed above, open an issue, share the link, describe what this tutorial is about and why you think it's better than the currently listed one. 



[Grider]: <https://www.udemy.com/course/ethereum-and-solidity-the-complete-developers-guide/>
[Eattheblocks]: <https://www.youtube.com/channel/UCZM8XQjNOyG2ElPpEUtNasA>
[AlchemyNFT]: <https://docs.alchemy.com/alchemy/tutorials/how-to-create-an-nft>
[ReactWebsite]: <https://www.youtube.com/watch?v=I2UBjN5ER4s&list=PLh8IMVX2eZaE3vmwkF9nBiS0nbNKHWpJq&index=14>
[TaskTrackerReact]: <https://www.youtube.com/watch?v=w7ejDZ8SWv8&list=PLh8IMVX2eZaE3vmwkF9nBiS0nbNKHWpJq&index=12>
[CSSCompleteCourse]: <https://www.youtube.com/watch?v=1Rs2ND1ryYc&list=PLh8IMVX2eZaFZiOqZhIsDe1j7o-HONaIY&index=2>
[CSSGrid]: <https://www.youtube.com/watch?v=68O6eOGAGqA&list=PLh8IMVX2eZaFZiOqZhIsDe1j7o-HONaIY&index=1>
[Remix]: <https://remix.ethereum.org/>
[VSCode]: <https://code.visualstudio.com/>
[Hardhat]: <https://hardhat.org/>
[Web3 Library]: <https://web3js.readthedocs.io/en/v1.5.2/getting-started.html>
[Etherjs]: <https://docs.ethers.io/v5/getting-started/>
[Mocha]: <https://mochajs.org/>
[Chai]: <https://www.chaijs.com/>
[Waffle]: <https://ethereum-waffle.readthedocs.io/en/latest/>
[hardhat's recommended choice]: <https://hardhat.org/guides/waffle-testing.html>
[Truffle]: <https://trufflesuite.com/>
[TypeScript Crash Course]: <https://www.youtube.com/watch?v=BCg4U1FzODs>
