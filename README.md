# 100 Days Of Blockchain Code - Log

## 100 Days Of Blockchain Code is a pledge to dedicate at least 1 hour of study or coding to blockchain development for 100 days
Inspired by [Siraj Raval's 100 Days Of ML Code challenge](https://www.youtube.com/watch?v=cuQMBj1cWPo)


### Day 1: July 18, 2018
##### Coding My Own Cryptocurrency on Ethereum

**Today's Progress**: Written First Smart Contract and started with coding front-end for ICO website.

**Thoughts**: I really struggled with having a test-driven development mindset. But getting the hang of it now.

**Link(s) to work**: [LabToken Repo](https://github.com/RoyVoetman/LabToken)

### Day 2: July 19, 2018
##### Coding My Own Cryptocurrency on Ethereum

**Today's Progress**: Deployed Smart Contract to Rinkeby test network

**Thoughts**: Tried to sync with the Rinkeby test network via `geth` but I got stuck on the last 60-70 blocks. Eventually solved this by running `geth` with the `--light` flag.

**Link(s) to work**: [LabToken Repo](https://github.com/RoyVoetman/LabToken)

### Day 3: July 20, 2018
##### Coding My Own Cryptocurrency on Ethereum

**Today's Progress**: Deployed ICO website to GitHub pages.

**Thoughts**: I struggled with loading all my css and js files with the right paths because for some weird reason the `app.js` file couldn't be accessed via GitHub pages.

**Link(s) to work**: [LabToken ICO website](https://royvoetman.github.io/LabToken/)

### Day 4: July 21, 2018
##### Coding My First DApp on Ethereum (Election DApp)

**Today's Progress**: Got started on coding the Election Smart Contract and added boiler plate code for the front-end.

**Thoughts**: I did some more research on ES6 Promises and found a cleaner way of writing promise chains with `async` and `await` instead of `.then(() => {})`. I also learned about the difference between a `mapping`, `array` and `struct` in Solidity. 

**Link(s) to work**: [Election DApp repo](https://github.com/RoyVoetman/Election-DApp)

### Day 5: July 22, 2018
##### Coding My First DApp on Ethereum (Election DApp)

**Today's Progress**: Added the core voting functionality to Smart Contract and front-end.

**Thoughts**: 

* Today I had a problem with listening for Smart Contract events when starting from `block 0`. This meant that all the previous events would trigger at the same time on a page reload. This resulted in unnecessary code execution.

* Found a way for handling errors with `async` functions without `try` and `catch` blocks.

**Reference(s)**: [Article: How to write without try-catch blocks in Javascript](https://blog.grossman.io/how-to-write-async-await-without-try-catch-blocks-in-javascript/)

**Link(s) to work**: [Election DApp repo](https://github.com/RoyVoetman/Election-DApp)

### Day 6: July 23, 2018
##### Coding My First DApp on Ethereum (Election DApp)

**Today's Progress**: Deployed front-end to IPFS.

**Thoughts**: At first at was not clear to me what the difference was between IPFS and IPNS but now I know that IPFS is the hash of the file and IPNS is the hash you can publish because that one isn't gonna change.

**Link(s) to work**:
 * [Election DApp repo](https://github.com/RoyVoetman/Election-DApp)
 * [IPFS Gateway](https://gateway.ipfs.io/ipns/QmQVEuk8x7por9xSJVNTTxRqTJWxspJt5GnrEmWxEt29rd/)
 
 ### Day 7: July 24, 2018
 ##### Coding My First DApp on Ethereum (Election DApp)
 
 **Today's Progress**: Added functionality for contract admin to dynamically add new candidates / Started refactoring Token Sale tests (`async await` instead of `then()`).
 
 **Thoughts**: I didn't really have any struggles today apart from Metamask caching some things about my local test network, fixed this by changing netwerk_id of test network.
 
 **Link(s) to work**:
  * [Election DApp repo](https://github.com/RoyVoetman/Election-DApp)
  * [LabToken ICO website](https://royvoetman.github.io/LabToken/)
  
   ### Day 8: July 25, 2018
   ##### Coding My First DApp on Ethereum (Election DApp)
   
   **Today's Progress**: Added functionality for contract admin to dynamically add new candidates in the front-end / Finished refactoring Token Sale tests (`async await` instead of `then()`).
   
   **Thoughts**: I faced a challenge by integrating special functionality for the Contract Owner because I didn't want everybody to know who the admin is so hard-coding the address or defining the 'admin' variable public wouldn't solve anything.
   
   Eventually, I created a getter function for the private 'admin' variable but added an 'onlyOwner' modifier to check if the address calling it is the owner. Then in the front-end, I wrapped the getter function in a 'try' block so the extra functionality would only be visable for the owner.
   
   **Link(s) to work**:
  * [Election DApp repo](https://github.com/RoyVoetman/Election-DApp)
  * [LabToken ICO website](https://royvoetman.github.io/LabToken/)
  
 ### Day 9: July 26, 2018
 ##### Coding My First DApp on Ethereum (Election DApp)
   
   **Today's Progress**: Deployed Election DApp to Rinkeby test network and deployed frontend to IPFS.
   
   **Thoughts**: Today I finished my first DApp! Really learning a lot by just doing, without this challenge I would have probably procrastinated on this project.
   
   **Link(s) to work**:
  * [Election DApp repo](https://github.com/RoyVoetman/Election-DApp)
  * [IPFS Gateway](https://gateway.ipfs.io/ipns/QmQVEuk8x7por9xSJVNTTxRqTJWxspJt5GnrEmWxEt29rd/)
  
    
 ### Day 10: July 27, 2018
   
   **Today's Progress**: Did more research on the possibilities/potentials of blockchain technology / Looked into the Drizzle front-end framework from truffle.
   
   **Thoughts**: Today there is a heat wave and because of this coding isn't really the best thing to do right now. But doing research on all the available tools and looking at how other people solve the problems they face when build DApps is also a very good learning opportunity.
   
   **Reference(s)**:
  * [Drizzle](https://truffleframework.com/docs/drizzle/getting-started)
  * [Video](https://www.youtube.com/watch?v=oCS05QSQ-1k)
  
 ### Day 11: July 28, 2018
   
   **Today's Progress**: Did research on NEO and EOS and what these technologies bring to the crypto space
   
   **Thoughts**: I personally think if Etheruem doesn't start improving it will be replaced by either NEO or EOS. My personal interest goes to EOS because of its low feeds and the use of an improved consensus protocol over regular PoS.
   
  **Reference(s)**:
  * [EOS](https://eos.io/)
  * [NEO](https://neo.org/)
  * [https://globalcoinreport.com/eos-vs-neo-which-one-will-replace-ethereum/](https://globalcoinreport.com/eos-vs-neo-which-one-will-replace-ethereum/)
  
### Day 12: July 29, 2018
##### Coding Smart Contracts on EOSIO
   
   **Today's Progress**: Started reading EOS's white paper and doing more research on EOS in general
   
   **Thoughts**: I think there is a very high potential for EOS to grow in the next few months/years. Really excited to see what will happen over time. I will definitely look into developing DApps for EOS.
   
  **Reference(s)**:
  * [EOS](https://eos.io/)
  * [EOS Whitepaper](https://github.com/EOSIO/Documentation/blob/master/TechnicalWhitePaper.md)
  
### Day 13: July 30, 2018
##### Coding Smart Contracts on EOSIO
   
  **Today's Progress**: Tried setting up EOS development environment.

  **Thoughts**: Today I learned about docker because the EOS documentation says that this is the quickest way to set up the development environment. The docker image is now successfully installed but I still can't execute commands like `nodeos`, `cleos`, and `keosd`.
   
  **Reference(s)**:
  * [EOS Quickstart](https://developers.eos.io/eosio-nodeos/docs/docker-quickstart)
  * [Docker](https://docs.docker.com/)
  
### Day 14: July 31, 2018
##### Coding Smart Contracts on EOSIO
   
  **Today's Progress**: Continued setting up EOS development environment.

  **Thoughts**: After some more in-depth research about docker I found out how to execute a command in your docker container. But this is a pain to write every time so I added the following aliases to my `.zshrc` file:
   * `alias cleos='docker exec -it eosio /opt/eosio/bin/cleos -u http://127.0.0.1:8888 --wallet-url http://127.0.0.1:8888'`
   * `alias nodeos='docker exec -it eosio /opt/eosio/bin/nodeos'`
   * `alias keosd='docker exec -it eosio /opt/eosio/bin/keosd'`
   
  **Reference(s)**:
  * [EOS Introduction to smart contracts](https://developers.eos.io/eosio-cpp/docs/introduction-to-smart-contracts)
  * [Docker exec](https://docs.docker.com/engine/reference/commandline/exec/)
  
### Day 15: August 1, 2018
##### Coding Smart Contracts on EOSIO
   
  **Today's Progress**: Begon developing HelloWorld smart contract with EOS

  **Thoughts**: Found out how to access the terminal of your Docker container and used the `eosiocpp` compiler (also added an alias to my `.zshrc` file). I struggled a bit with keeping track of all my different PKeys and SKeys all my different accounts but everything is very well documented so I am still excited to learn more!
   * `docker exec -it <container_id> /bin/bash`
   * `alias eosiocpp='docker exec -it eosio /opt/eosio/bin/eosiocpp'`
   
  **Reference(s)**:
  * [Documentation Guide](https://developers.eos.io/eosio-cpp/docs/hello-world)
  
### Day 16: August 2, 2018
##### Coding Smart Contracts on EOSIO
   
 **Today's Progress**: Finished creating HelloWorld contract with EOS and Did more research on using Docker

 **Thoughts**: Found out about Dockers `-v` flag for `VOLUME (shared filesystems)` this prevents u having to rebuild the Docker image every time you make a change to your code. This makes the Docker developing experience way better.
   
  **Reference(s)**:
  * [Stack overflow post](https://stackoverflow.com/questions/24272535/rebuild-container-after-each-change)
  
  **Link(s) to work**:
  * [Hello world smart contract](https://github.com/RoyVoetman/EOS-Starter-kit/tree/master/helloWorld)
  
### Day 17: August 3, 2018
##### Coding Smart Contracts on EOSIO
   
**Today's Progress**: Finally successfully setup a complete EOS development environment with Docker

**Thoughts**: Yesterday I already had a 'working' development environment but my wallets didn't sync with my local environment so every time I booted up the docker image I would need to recreate all my wallets/keys. I finally solved this by reading the in-depth documentation about `cleos` and `keosd`. When I knew where the wallets/keys where stored I added a `-v` flag so that the folder would sync to my local environment.

After that, I thought that it still didn't work because `cleos wallet list` still gave an empty array but after a lot of debugging I found out that only my unlocked wallets are shown with `cleos wallet list`.
   
  **Reference(s)**:
  * [Learn about wallets keys and accounts with cleos](https://eosio-nodeos.readme.io/docs/learn-about-wallets-keys-and-accounts-with-cleos)
  
  ### Day 18: August 4, 2018
  ##### Coding Smart Contracts on EOSIO
   
**Today's Progress**: Read the 'EOS Overview' / Reread 'EOS Getting started guide'.

**Thoughts**: After having successfully read the 'EOS Overview', pages I only briefly studied last time, it became much clearer to me how everything works. 

With my new knowledge, I reread the 'EOS Getting started guide'. Now that I finished that I feel ready to begin coding my own smart contract tomorrow.

  **Reference(s)**:
  * [Communication model](https://developers.eos.io/eosio-cpp/docs/communication-model)
  * [File structure](https://developers.eos.io/eosio-cpp/docs/file-structure)
  
### Day 19: August 5, 2018
##### Coding Smart Contracts on EOSIO
   
**Today's Progress**: Started following EOS Developement turorial.

**Thoughts**: After installing/configuring the CLion IDE, I followed the EOS development tutorial by Infinitexlabs. Really like the tutorial and require knowledge level. Struggling a little with all the C++ code because I only now C. C++ will defiantly be a something to look into.

  **Reference(s)**:
  * [EOS Developement turorial](https://infinitexlabs.com/eos-development-tutorial-part-1/)
  
    
### Day 20: August 6, 2018
##### Coding Smart Contracts on EOSIO
   
**Today's Progress**: Followed C++ tutorials.

**Thoughts**: Because I already know C, most of the syntax was pretty straightforward. But I am still struggling with the difference between `this` and `self`.

  **Reference(s)**:
  * [Derek Banas C++ Problem solving](https://www.youtube.com/watch?v=Rub-JsjMhWY)
  * [Derek Banas C++](https://www.youtube.com/watch?v=N5HgK1bTLOg)
  
  ### Day 21: August 7, 2018
  ##### Coding Smart Contracts on EOSIO
   
**Today's Progress**: Continued following EOS Developement turorial / Watched EOS Hackethon finals.

**Thoughts**: It's really awesome to see what other people are creating with blockchain. Watching the pitches of the hackathon finalists also gives you inside in their work-flow and thought process so it's a great learning opportunity.

  **Reference(s)**:
  * [EOS Developement turorial](https://infinitexlabs.com/eos-development-tutorial-part-2/)
  * [Hackethon finals](https://www.youtube.com/watch?v=_JIaooJeNdk)

  ### Day 22: August 8, 2018
  ##### Coding Smart Contracts on EOSIO
   
**Today's Progress**: Moved from using Docker to building from source.

**Thoughts**: I found that the docker image was great for getting up and running but it had some limitations when it came to developing. So I uninstalled the docker image and with the provided build script from EOS, I build from source. After look at the 'Build options' section in the docs I found out it is possible to use the docker image for development but it required some extra steps. But because I now already had a local EOS build I didn't saw a need to switch back to Docker.

  **Reference(s)**:
  * [EOS Build docs](https://developers.eos.io/eosio-nodeos/docs/autobuild-script)
  * [Build issue](https://github.com/EOSIO/eos/issues/2392)
  
### Day 23: August 9, 2018
##### Coding Smart Contracts on EOSIO
   
**Today's Progress**: Followed webinar about developing with EOS / Found out the difference between an OwnerKey and ActiveKey.

**Thoughts**: Finally, I can really get to the coding, I have setup Nodeos Keosd and Cleos and I have configured CLion to work with `eoslib`. Also did so research about the need of an `owner key` and `active key`, your active key and owner key can really do everything a normal private key could do, except that your owner key can overwrite the active key so when you think your active key has been compromised you use your owner key to overwrite the active key.

  **Reference(s)**:
  * [EOS webinar](  https://www.youtube.com/watch?v=E3Tx2DseLGE)
  * [OwnerKey ActiveKey Reddit](https://www.reddit.com/r/eos/comments/8vl8b1/manage_your_owner_and_active_keypairs_to_get_cold/)
  
### Day 24: August 10, 2018
##### Coding Smart Contracts on EOSIO

**Today's Progress**: Continued following webinar about developing with EOS.

**Thoughts**: My ideal setup would be to have the EOSIO software is my `~/Library` folder and my custom contract is a special `~/Desktop/dapps` folder on my desktop. So I moved the 'EOS' folder to `~/Library/eosio` and created a bash function for compiling:
```
eos-compile() {
eosiocpp -o "$1.wast" "$1.cpp"
eosiocpp -g "$1.abi" "$1.hpp"
}
```
The problem I encountered is that I don't have access to the 'eoslib' inside of this folder. Still trying to figure out how to solve this problem.

  **Reference(s)**:
  * [EOS webinar](https://www.youtube.com/watch?v=E3Tx2DseLGE)
  
  ### Day 25: August 11, 2018
  ##### Coding Smart Contracts on EOSIO

**Today's Progress**: Finished following webinar about developing with EOS. / Did some research about WASM

**Thoughts**: After the webinar, there was a Q&A and that really help to solve some questions I have been having. They also pointed me out to an `EOS Developers` telegram group which is the perfect place to ask your questions about EOS development.

I Also, did some research on WASM (WebAssembly) because EOS uses WASM to store contracts on the EOS blockchain.

  **Reference(s)**:
  * [EOS webinar](https://www.youtube.com/watch?v=E3Tx2DseLGE)
  * [WebAssembly Demystified](https://www.youtube.com/watch?v=6Y3W94_8scw)
  * [EOS Developers telegram](https://t.me/joinchat/EaEnSUPktgfoI-XPfMYtcQ)
  
### Day 26: August 12, 2018
##### Coding Smart Contracts on EOSIO

**Today's Progress**: Got started on my own election smart contract for EOS.

**Thoughts**: Finally started developing my own smart contract! Although I am still struggling with all the EOSLIB custom data types, the `contracts` folder from EOSIO is a great resource.

  **Reference(s)**:
  * [EOSIO/eosio/contracts](https://github.com/EOSIO/eos/tree/master/contracts)
  * [CodingWithCrypto Youtube Channel](https://www.youtube.com/channel/UC4U1e94pVzGceaxJw3WCkRQ)
  
  **Link(s) to work**:
  * [Smart Contract](https://github.com/RoyVoetman/EOSIO-Contracts/tree/master/election)
  
### Day 27: August 13, 2018
##### Coding Smart Contracts on EOSIO

**Today's Progress**: Implemented voting logic in my election smart contract for EOS.

**Thoughts**: It's really difficult to develop on a platform that is still under heavy production. So parts of the EOS.org documentation are out of date so you need to ask people on for example Telegram to know what is the right way to implement certain logic.

  **Reference(s)**:
  * [C++/C Function Reference](https://developers.eos.io/eosio-cpp/reference)
  
  **Link(s) to work**:
  * [Smart Contract](https://github.com/RoyVoetman/EOSIO-Contracts/tree/master/election)
  
  ### Day 28: August 14, 2018
  ##### Coding Smart Contracts on EOSIO
  
  **Today's Progress**: Finished my election smart contract for EOS.
  
  **Thoughts**: Still having problems with compiling my contract to WASM with the `eosiocpp` compiler. After that I tried build it in CLion with CMake but also without success. Hopefully I will figure it out tomorrow.
  
  But besides the problems with compiling I am really glad that I finished my first EOS Smart Contract!
  
   **Reference(s)**:
   * [C++/C Function Reference](https://developers.eos.io/eosio-cpp/reference)
    
   **Link(s) to work**:
   * [Smart Contract](https://github.com/RoyVoetman/EOSIO-Contracts/tree/master/election)
    
### Day 29: August 15, 2018
##### Coding Smart Contracts on EOSIO
  
  **Today's Progress**: Uninstalled EOS?!
  
  **Thoughts**: After a lot of research I still couldn't find out what the problem was with my `eosiocpp` compiler. But a great thanks to the EOS Developers Telegram group for helping me out. It seems that when I built EOS there was a bug in the source code. They fixed this later so that would mean that I had to uninstall EOS and rebuild it again.

   I saw this as the perfect opportunity to go from a local build to a VM build. So tomorrow I will build EOS again but then on a Linux VM.
 
  *Btw: EOS v1.2.0 just came out and it says the `eosiocpp` executable is now deprecated. We should now use `eosio-cpp` from the `eosio.wasmsdk`*
  
   **Reference(s)**:
   * [EOS v1.2.0](https://github.com/EOSIO/eos/releases/tag/v1.2.0)
   * [WASM SDK](https://github.com/EOSIO/eosio.wasmsdk)
   * [EOS Developers telegram](https://t.me/joinchat/EaEnSUPktgfoI-XPfMYtcQ)
   
### Day 30: August 16, 2018
##### Coding Smart Contracts on EOSIO
  
**Today's Progress**: Installed EOS on Linux VM / Started coding a TODO smart contract

**Thoughts**: After installing EOS on a VM I faced the same issues I had when using Docker. CLion didn't have access to all the needed libraries, Compiling still didn't work properly, etc.

At first, EOS looked really awesome and it still is for sure but atm the development workflow is kind of pain. Everything is under heavy development, the docs are sometimes out of date with the latest updates and sometimes when a new update came out you have to rebuild EOS (which takes a lot of time).

Because of this, I am thinking about finishing my new TODO list contract but after that leaving EOS for what it is right now. It learned me a lot of things about, Wallets, Keys, C++ and running your own node so I don't see it as a waste of time. I will definitely keep an eye out for the project but as of right now I will focus on some other cool skills I want to master.
  
   **Reference(s)**:
   * [Setting up EOS on a Linux VM](https://www.youtube.com/watch?v=glB6UPHo1rA)
   
### Day 31: August 17, 2018
##### Coding Smart Contracts on EOSIO
  
**Today's Progress**: Finished coding a TODO smart contract / Updated README's

**Thoughts**: Finished coding a TODO smart contract. I learned about using the multi_index functionality to its full potential by actually defining multiple indexes.

Updated all repos that are especially for this challenge with a footer:

> Part of my [100 days of blockchain code challenge](https://github.com/RoyVoetman/100-days-of-blockchain-code)
  
   **Link(s) to work**:
   * [TODO list smart contract](https://github.com/RoyVoetman/EOSIO-Contracts/tree/master/todo)
   
### Day 32: August 18, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Brainstormed about new a new project

**Thoughts**: I really wanted to create a game with blockchain technology and an educational aspect. So I started thinking about the gameplay. When I decided I wanted to make an online card dueling/trading game I started creating a mind map about what the game would look like and what tools I would need for creating it.
  
   **Link(s) to work**:
   * [Mind-map](https://github.com/RoyVoetman/Etherlanders/blob/master/docs/Mind-map.png)
   
### Day 33: August 19, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Updated mind-map / Read crypto kitties whitepaper

**Thoughts**: After brainstorming about what parts of the application will be open source or closed source I did some research on popular DApp games. Crypto kitties is a very popular project so reading their white-paper can help a lot when I am going to write my own.
  
   **Link(s) to work**:
   * [Mind-map](https://github.com/RoyVoetman/Etherlanders/blob/master/docs/Mind-map.png)
   
   **Reference(s)**:
   * [Crypto kitties whitepaper](http://upyun-assets.ethfans.org/uploads/doc/file/25583a966d374e30a24262dc5b4c45cd.pdf?_upd=CryptoKitties_WhitePapurr_V2.pdf)
      
### Day 34: August 20, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Started writing a white paper

**Thoughts**: Today I learned a lot about white papers. I have never written a white paper before so I am looking how other crypto projects have written their white papers. Besides that, I tried to come up with a name for the game.
  
   **Link(s) to work**:
   * [White paper](https://github.com/RoyVoetman/Etherlanders/wiki/Etherlanders-%7C-White-paper)
   
### Day 35: August 21, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Started writing the introduction for the white paper

**Thoughts**: When writing the introduction, it really challenged me to visualize what I wanted the game to look like. As for now I still don't really know how the game would look like and what kind of gameplay it would be. I tried to keep the introduction as general as possible so I can come back later and change it when I have a better overview on how the game would exactly look like.

   **Link(s) to work**:
   * [White paper](https://github.com/RoyVoetman/Etherlanders/wiki/Etherlanders-%7C-White-paper)
   
### Day 36: August 22, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Came up with the name! / Brainstormed about the game itself

**Thoughts**: After some thinking I finally got an awesome name: *Etherlanders*.

I also thought about the game and I came up with the idea to replace the concept of cards with actual 3D Models of the creatures on the cards. This would require a lot a graphical work but definitely the main goal for now, if it's not doable to create 3D Model we could always fall back to just using cards.

But moving away from cards also leaves us with a problem, how will the *Etherlanders* be distributed? I have been thinking about replacing the card packs with just packs *or* hatching *Etherlanders* out of eggs *or* selling *Etherlanders* on a marketplace. For now, I haven't decided what to go for and I didn't have time to update the whitepaper so I will leave that for tomorrow.

   **Link(s) to work**:
   * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders)
   
      
### Day 37: August 23, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Finished the white papers Introduction

**Thoughts**: Today I took some time to update my mind map with the new ideas from yesterday. I also finished the white papers 'Introduction' section where I was challenged to really think about how I wanted this new concept to work.

To get back to the discussion about how to Etherlanders will be distributed. I choose to replace the card packs with just regular packs whereby each pack contains 1 creature.
 
 **Link(s) to work**:
 * [White paper](https://github.com/RoyVoetman/Etherlanders/wiki/Etherlanders-%7C-White-paper)
 * [Mind-map](https://github.com/RoyVoetman/Etherlanders/blob/master/docs/Mind-map.png)

### Day 38: August 24, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Worked on white paper.

**Thoughts**: Really enjoying this project because I always wanted to create my own fictional world and now I can combine it with programming. 

I also found some friends that want to help further develop this project so looking forward to it!
 
 **Link(s) to work**:
 * [White paper](https://github.com/RoyVoetman/Etherlanders/wiki/Etherlanders-%7C-White-paper)
 
### Day 39: August 25, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Improved white papers introduction section / Written white papers Education and Team section.

**Thoughts**: Getting a lot of inspiration by reading white papers of other DApps. Writing a white paper is not only learning me about Blockchain but also about English grammar, documentation and it is learning me about how to make a game in general.

I also like that I reserve at least 1 hour every day to work on this project because other while I know I would have procrastinated on this a lot!
 
  **Reference(s)**:
  * [Crypto kitties whitepaper](http://upyun-assets.ethfans.org/uploads/doc/file/25583a966d374e30a24262dc5b4c45cd.pdf?_upd=CryptoKitties_WhitePapurr_V2.pdf)
  * [Ethereum whitepaper](https://github.com/ethereum/wiki/wiki/White-Paper)
 
 **Link(s) to work**:
 * [White paper](https://github.com/RoyVoetman/Etherlanders/wiki/Etherlanders-%7C-White-paper)
  
### Day 40: August 26, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Began writing white papers Future section.

**Thoughts**: Really looking forward to writing the actual story line after I finished the white paper. And I am of course excited about all the new challenges this project will bring.
 
 **Link(s) to work**:
 * [White paper](https://github.com/RoyVoetman/Etherlanders/wiki/Etherlanders-%7C-White-paper)
 
### Day 41: August 27, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Finished writing white papers Future and Conclusion section.

**Thoughts**: After finishing the white paper, except for the sections battling and puzzles, I started to do some research about creating a fantasy world. There are some great resources out there that help you with questions you have to ask yourself when creating a fantasy world.

The battling and puzzles sections are still to be continued because I haven't figured out yet what the actual game-play will look like. I am planning a brainstorm session with the current team so we can all agree on a fun but also feasible game-play.

  **Reference(s)**:
  * [Creating a fantasy world?](https://www.nownovel.com/blog/10-questions-ask-fantasy-world/)
  * [How to create a fantasy world that everyone will believe](https://www.nownovel.com/blog/how-to-create-a-fantasy-world/)
 
 **Link(s) to work**:
 * [White paper](https://github.com/RoyVoetman/Etherlanders/wiki/Etherlanders-%7C-White-paper)
 * [Story line](https://github.com/RoyVoetman/Etherlanders/wiki/Etherlanders-%7C-Storyline)
 
 ### Day 42: August 28, 2018
 ##### Developing my own game on Ethereum
 
**Today's Progress**: Finished writing the white papers Battle section.

**Thoughts**: I tried to start on writing the Storyline but I thought it would be more sensible to finish the 'Battling' and 'Puzzles' section first. I didn't want to make the battling to complex because it is not the core aspect of the game. So I looked at how other games integrated a combat-like experience in their game. And created a mix of all the ideas that I liked.

 **Link(s) to work**:
 * [White paper](https://github.com/RoyVoetman/Etherlanders/wiki/Etherlanders-%7C-White-paper)
 
  ### Day 43: August 29, 2018
  ##### Developing my own game on Ethereum
 
**Today's Progress**: Finished writing the white paper! / Added boilerplate code to the project.

**Thoughts**: Really glad about finishing my first white paper although there surely are some sections that could be improved, it still is a big milestone. Next to hitting that milestone I also added the boilerplate to start developing the actual Smart contracts and UI. Really looking forward to coding this DApp.

 **Link(s) to work**:
 * [White paper](https://github.com/RoyVoetman/Etherlanders/wiki/Etherlanders-%7C-White-paper)
 * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders)

### Day 44: August 30, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Implemented the OpenZeppelin framework for building secure smart contracts

**Thoughts**: I already new about OpenZeppeling being a framework that helped you write secure smart contracts but I didn't know it did most of the work for you. Right now I only have to extend my contract from the OpenZeppelins `ERC721Token` contract. The only thing I have to after that is to give the token a `name` and a `symbol` and the boilerplate for the `ERC721` token is already set up! And OpenZeppelin works with truffle right out of the box!

  **Reference(s)**:
  * [Open zeppelin](https://github.com/OpenZeppelin/openzeppelin-solidity)
  * [The anatomy of ERC721](https://medium.com/crypto-currently/the-anatomy-of-erc721-e9db77abfc24)
 
 **Link(s) to work**:
 * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)

### Day 45: August 31, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Implemented minting function / getter function

**Thoughts**: Struggling a bit to get back into the test-driven development work-flow but overall enjoying working on this project. Creating something where the borders are only determined by your own imagination is an amazing experience.

  **Reference(s)**:
  * [Open zeppelin](https://github.com/OpenZeppelin/openzeppelin-solidity)
  * [Truffle](https://truffleframework.com/)
 
 **Link(s) to work**:
 * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)
 
 ### Day 46: September 1, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Improved minting function / researched cryptokitties smart contract

**Thoughts**: I really love that the Ethereum blockchain is open source because you can look up other smart contracts and learn from how they implemented certain logic. I am struggling a bit with how I want to create the Etherlanders because creating truly random strings or numbers on the blockchain is impossible because every computer on the network needs to run the same code at different times. As for now, I see no other option than including some user-provided number generated client side. I will definitely do more research on this topic.

  **Reference(s)**:
  * [Crypto kitties smart contract](https://etherscan.io/address/0x06012c8cf97bead5deae237070f9587f8e7a266d#code)
 
 **Link(s) to work**:
 * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)
 
### Day 47: September 2, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Added attacks and categories to contract / Improved minting function

**Thoughts**: Only owners will be allowed to `mint` new Etherlanders so what I ended up doing is running the `keccak256` function on the provided `_name` parameter. This will give me a bunch of numbers then I will apply modules on the result to get the preferred amount of numbers.

I also found out that it is also good to keep in mind that every computation in Solditiy costs gas. I will have to research how to optimize my code so it will cost less gas. It really is a different mindset you have to get into.
 
 **Link(s) to work**:
 * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)
 
### Day 48: September 3, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Found out about CryptoZombies / Added NewEtherlander event

**Thoughts**: Follow a few lessons from cryptozombies, a website where you can learn to build your own game with Solidity. I also added a new event but when I tried to write a test for it I got stuck. Later I found out that the ERC721 token also triggers a Transfer event and I didn't account for that in my test. 

 **Reference(s)**:
 * [Crypto zombies](https://cryptozombies.io/)
 
 **Link(s) to work**:
 * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)
 
 ### Day 49: September 4, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Begon writing storyline

**Thoughts**: I really love exploring the galaxy and that is why I want to bring that passion to life in the story line. I will definitely do more research on the expansion our sun will go through when it has fused all of its hydrogen. Still, love working on this project and still like the idea of working on it every day for 1 hour so you really see progress has been made.

 **Reference(s)**:
 * [Will Earth survive when the sun becomes a red giant?](https://phys.org/news/2016-05-earth-survive-sun-red-giant.html)
 * [Red giant stars](https://www.space.com/22471-red-giant-stars.html)
 
 **Link(s) to work**:
 * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)
