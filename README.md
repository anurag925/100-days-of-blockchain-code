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
   
   **Today's Progress**: Did research on NEO and EOS and what these technologies bring to the crypto space.
   
   **Thoughts**: I personally think if Etheruem doesn't start improving it will be replaced by either NEO or EOS. My personal interest goes to EOS because of its low feeds and the use of an improved consensus protocol over regular PoS.
   
  **Reference(s)**:
  * [EOS](https://eos.io/)
  * [NEO](https://neo.org/)
  * [https://globalcoinreport.com/eos-vs-neo-which-one-will-replace-ethereum/](https://globalcoinreport.com/eos-vs-neo-which-one-will-replace-ethereum/)
  
### Day 12: July 29, 2018
##### Coding Smart Contracts on EOSIO
   
   **Today's Progress**: Started reading EOS's white paper and doing more research on EOS in general.
   
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
   
  **Today's Progress**: Begon developing HelloWorld smart contract with EOS.

  **Thoughts**: Found out how to access the terminal of your Docker container and used the `eosiocpp` compiler (also added an alias to my `.zshrc` file). I struggled a bit with keeping track of all my different PKeys and SKeys all my different accounts but everything is very well documented so I am still excited to learn more!
   * `docker exec -it <container_id> /bin/bash`
   * `alias eosiocpp='docker exec -it eosio /opt/eosio/bin/eosiocpp'`
   
  **Reference(s)**:
  * [Documentation Guide](https://developers.eos.io/eosio-cpp/docs/hello-world)
  
### Day 16: August 2, 2018
##### Coding Smart Contracts on EOSIO
   
 **Today's Progress**: Finished creating HelloWorld contract with EOS and Did more research on using Docker.

 **Thoughts**: Found out about Dockers `-v` flag for `VOLUME (shared filesystems)` this prevents u having to rebuild the Docker image every time you make a change to your code. This makes the Docker developing experience way better.
   
  **Reference(s)**:
  * [Stack overflow post](https://stackoverflow.com/questions/24272535/rebuild-container-after-each-change)
  
  **Link(s) to work**:
  * [Hello world smart contract](https://github.com/RoyVoetman/EOS-Starter-kit/tree/master/helloWorld)
  
### Day 17: August 3, 2018
##### Coding Smart Contracts on EOSIO
   
**Today's Progress**: Finally successfully setup a complete EOS development environment with Docker.

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

**Today's Progress**: Finished following webinar about developing with EOS. / Did some research about WASM.

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
  
**Today's Progress**: Installed EOS on Linux VM / Started coding a TODO smart contract.

**Thoughts**: After installing EOS on a VM I faced the same issues I had when using Docker. CLion didn't have access to all the needed libraries, Compiling still didn't work properly, etc.

At first, EOS looked really awesome and it still is for sure but atm the development workflow is kind of pain. Everything is under heavy development, the docs are sometimes out of date with the latest updates and sometimes when a new update came out you have to rebuild EOS (which takes a lot of time).

Because of this, I am thinking about finishing my new TODO list contract but after that leaving EOS for what it is right now. It learned me a lot of things about, Wallets, Keys, C++ and running your own node so I don't see it as a waste of time. I will definitely keep an eye out for the project but as of right now I will focus on some other cool skills I want to master.
  
   **Reference(s)**:
   * [Setting up EOS on a Linux VM](https://www.youtube.com/watch?v=glB6UPHo1rA)
   
### Day 31: August 17, 2018
##### Coding Smart Contracts on EOSIO
  
**Today's Progress**: Finished coding a TODO smart contract / Updated README's.

**Thoughts**: Finished coding a TODO smart contract. I learned about using the multi_index functionality to its full potential by actually defining multiple indexes.

Updated all repos that are especially for this challenge with a footer:

> Part of my [100 days of blockchain code challenge](https://github.com/RoyVoetman/100-days-of-blockchain-code)
  
   **Link(s) to work**:
   * [TODO list smart contract](https://github.com/RoyVoetman/EOSIO-Contracts/tree/master/todo)
   
### Day 32: August 18, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Brainstormed about new a new project.

**Thoughts**: I really wanted to create a game with blockchain technology and an educational aspect. So I started thinking about the gameplay. When I decided I wanted to make an online card dueling/trading game I started creating a mind map about what the game would look like and what tools I would need for creating it.
  
   **Link(s) to work**:
   * [Mind-map](https://github.com/RoyVoetman/Etherlanders/blob/master/docs/Mind-map.png)
   
### Day 33: August 19, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Updated mind-map / Read crypto kitties whitepaper.

**Thoughts**: After brainstorming about what parts of the application will be open source or closed source I did some research on popular DApp games. Crypto kitties is a very popular project so reading their white-paper can help a lot when I am going to write my own.
  
   **Link(s) to work**:
   * [Mind-map](https://github.com/RoyVoetman/Etherlanders/blob/master/docs/Mind-map.png)
   
   **Reference(s)**:
   * [Crypto kitties whitepaper](http://upyun-assets.ethfans.org/uploads/doc/file/25583a966d374e30a24262dc5b4c45cd.pdf?_upd=CryptoKitties_WhitePapurr_V2.pdf)
      
### Day 34: August 20, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Started writing a white paper.

**Thoughts**: Today I learned a lot about white papers. I have never written a white paper before so I am looking how other crypto projects have written their white papers. Besides that, I tried to come up with a name for the game.
  
   **Link(s) to work**:
   * [White paper](https://github.com/RoyVoetman/Etherlanders/wiki/Etherlanders-%7C-White-paper)
   
### Day 35: August 21, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Started writing the introduction for the white paper.

**Thoughts**: When writing the introduction, it really challenged me to visualize what I wanted the game to look like. As for now I still don't really know how the game would look like and what kind of gameplay it would be. I tried to keep the introduction as general as possible so I can come back later and change it when I have a better overview on how the game would exactly look like.

   **Link(s) to work**:
   * [White paper](https://github.com/RoyVoetman/Etherlanders/wiki/Etherlanders-%7C-White-paper)
   
### Day 36: August 22, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Came up with the name! / Brainstormed about the game itself.

**Thoughts**: After some thinking I finally got an awesome name: *Etherlanders*.

I also thought about the game and I came up with the idea to replace the concept of cards with actual 3D Models of the creatures on the cards. This would require a lot a graphical work but definitely the main goal for now, if it's not doable to create 3D Model we could always fall back to just using cards.

But moving away from cards also leaves us with a problem, how will the *Etherlanders* be distributed? I have been thinking about replacing the card packs with just packs *or* hatching *Etherlanders* out of eggs *or* selling *Etherlanders* on a marketplace. For now, I haven't decided what to go for and I didn't have time to update the whitepaper so I will leave that for tomorrow.

   **Link(s) to work**:
   * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders)
   
      
### Day 37: August 23, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Finished the white papers Introduction.

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
  
**Today's Progress**: Implemented the OpenZeppelin framework for building secure smart contracts.

**Thoughts**: I already new about OpenZeppeling being a framework that helped you write secure smart contracts but I didn't know it did most of the work for you. Right now I only have to extend my contract from the OpenZeppelins `ERC721Token` contract. The only thing I have to after that is to give the token a `name` and a `symbol` and the boilerplate for the `ERC721` token is already set up! And OpenZeppelin works with truffle right out of the box!

  **Reference(s)**:
  * [Open zeppelin](https://github.com/OpenZeppelin/openzeppelin-solidity)
  * [The anatomy of ERC721](https://medium.com/crypto-currently/the-anatomy-of-erc721-e9db77abfc24)
 
 **Link(s) to work**:
 * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)

### Day 45: August 31, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Implemented minting function / getter function.

**Thoughts**: Struggling a bit to get back into the test-driven development work-flow but overall enjoying working on this project. Creating something where the borders are only determined by your own imagination is an amazing experience.

  **Reference(s)**:
  * [Open zeppelin](https://github.com/OpenZeppelin/openzeppelin-solidity)
  * [Truffle](https://truffleframework.com/)
 
 **Link(s) to work**:
 * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)
 
### Day 46: September 1, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Improved minting function / researched cryptokitties smart contract.

**Thoughts**: I really love that the Ethereum blockchain is open source because you can look up other smart contracts and learn from how they implemented certain logic. I am struggling a bit with how I want to create the Etherlanders because creating truly random strings or numbers on the blockchain is impossible because every computer on the network needs to run the same code at different times. As for now, I see no other option than including some user-provided number generated client side. I will definitely do more research on this topic.

  **Reference(s)**:
  * [Crypto kitties smart contract](https://etherscan.io/address/0x06012c8cf97bead5deae237070f9587f8e7a266d#code)
 
 **Link(s) to work**:
 * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)
 
### Day 47: September 2, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Added attacks and categories to contract / Improved minting function.

**Thoughts**: Only owners will be allowed to `mint` new Etherlanders so what I ended up doing is running the `keccak256` function on the provided `_name` parameter. This will give me a bunch of numbers then I will apply modules on the result to get the preferred amount of numbers.

I also found out that it is also good to keep in mind that every computation in Solditiy costs gas. I will have to research how to optimize my code so it will cost less gas. It really is a different mindset you have to get into.
 
 **Link(s) to work**:
 * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)
 
### Day 48: September 3, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Found out about CryptoZombies / Added NewEtherlander event.

**Thoughts**: Follow a few lessons from cryptozombies, a website where you can learn to build your own game with Solidity. I also added a new event but when I tried to write a test for it I got stuck. Later I found out that the ERC721 token also triggers a Transfer event and I didn't account for that in my test. 

 **Reference(s)**:
 * [Crypto zombies](https://cryptozombies.io/)
 
 **Link(s) to work**:
 * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)
 
### Day 49: September 4, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Started writing storyline.

**Thoughts**: I really love exploring the galaxy and that is why I want to bring that passion to life in the story line. I will definitely do more research on the expansion our sun will go through when it has fused all of its hydrogen. Still, love working on this project and still like the idea of working on it every day for 1 hour so you really see progress has been made.

 **Reference(s)**:
 * [Will Earth survive when the sun becomes a red giant?](https://phys.org/news/2016-05-earth-survive-sun-red-giant.html)
 * [Red giant stars](https://www.space.com/22471-red-giant-stars.html)
 
 **Link(s) to work**:
 * [Etherlanders Storyline](https://github.com/RoyVoetman/Etherlanders/wiki/Etherlanders-%7C-Storyline)
 
### Day 50: September 5, 2018
##### Developing my own game on Ethereum
  
**Today's Progress**: Finished history section of the storyline.

**Thoughts**: After finishing the history section of the storyline I wanted to know more about where to start when I want to create a map for the world. I found a great video series that I started watching. I hope that in a few days I will have a map of the world but I still haven't figured out what kind of landscape the Earth will be.

So there are some challenges on the road but I like challenges and I am interested to see the solutions I will come up with.

 **Reference(s)**:
 * [Drawing a Fantasy Map](https://www.youtube.com/watch?v=p1eo-SzLCcY)
 * [How to build a fictional world - Kate Messner](https://www.youtube.com/watch?v=ZQTQSbjecLg)
 
 **Link(s) to work**:
 * [Etherlanders Storyline](https://github.com/RoyVoetman/Etherlanders/wiki/Etherlanders-%7C-Storyline)

> Missed **September 6** due to personal reasons

### Day 51: September 7, 2018

**Today's Progress**: Followed YouTube tutorials to deepen my understanding of working with OpenZeppelin.

**Thoughts**: Although this video series isn't about an ERC721 token it still learned me a lot about how to work with the openzeppelin library. Looking at the openzeppelin library on GitHub is also a great resource because you can see how they test their contracts.

I already made use of the `async await` syntax but I use `it()` for every assertion but they also use `describe` and `context` nested around a group of `it()` assertions. And the use of the `beforeEach()` function is also really powerful for logic that needs to be executed before every test (e.g. retrieving the contract instance).

 **Reference(s)**:
 * [Youtube video 1](https://www.youtube.com/watch?v=2IqsgSyA8BQ)
 * [Youtube video 2](https://www.youtube.com/watch?v=ir-IRmMTG4Q)
 * [OpenZeppelin](https://github.com/OpenZeppelin/openzeppelin-solidity)
 
 ### Day 52: September 8, 2018
 ##### Developing my own game on Ethereum

**Today's Progress**: Refactored unit tests.

**Thoughts**: Put the new knowledge to use by refactoring all the existing unit tests to the new design pattern (i.e. the use of `describe`, `context`, `it`, etc.). 

Again the OpenZeppelin library was very helpful. They gave me the idea of renaming the `modules` folder to the `helpers` folder and renaming the `Try` module/helper to `assertRevert`. 

 **Reference(s)**:
 * [OpenZeppelin unit tests](https://github.com/OpenZeppelin/openzeppelin-solidity/tree/master/test)
 
 
 ### Day 53: September 9, 2018
 ##### Developing my own game on Ethereum

**Today's Progress**: Documented all smart contract functions / Added getEtherlanderByAddress function.

**Thoughts**: Learned about asserting arrays with the '.should' design pattern (`array1.should.deep.equal(array2)`). And I found out that `solc` (i.e. The solidity compiler) actually looks at the documentation blocks if you use the `@param` and `@return` syntax, this prevents your doc blocks becoming out of date when you forget to update them.

 **Reference(s)**:
 * [OpenZeppelin unit tests](https://github.com/OpenZeppelin/openzeppelin-solidity/tree/master/test)
  
 **Link(s) to work**:
 * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)
 
 ### Day 54: September 10, 2018
 ##### Developing my own game on Ethereum

**Today's Progress**: Improved smart contract logic for better integration with the ERC721 token standard.

**Thoughts**: I refactored some smart contract logic because it was redundant, apparently it was already taken care of by the OpenZeppelins ERC721 token smart contract.

And I learned about how to assert that a variable is a certain data-type with `variable.should.be.an('datatype');`.
  
 **Link(s) to work**:
 * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)
 
 ### Day 55: September 11, 2018
 ##### Developing my own game on Ethereum

**Today's Progress**: Added a BuyTokens function / Continued watching  youtube tutorial series.

**Thoughts**: Today I struggled a bit with testing if a function returned an integer/number. Of course with web3 the function will return a `BigNumber` but even after calling the `.toNumber()` function on it `variable.should.be.an('integer');` still didn't work. As it turns out, JavaScript doesn't have a separate `integer` type. Everything is a floating point number, which would be of data type number.
  
 **Reference(s)**:
 * [Unit testing integers](https://stackoverflow.com/questions/23597475/chai-unittesting-expect42-to-be-aninteger/23597645)
 * [YouTube video 3](https://www.youtube.com/watch?v=wfzTtbZEJP8&index=3&list=PLS5SEs8ZftgULF-lbxy-is9x_7mTMHFIN)
 
 **Link(s) to work**:
 * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)
 
  ### Day 56: September 12, 2018
 ##### Developing my own game on Ethereum

**Today's Progress**: Read article series about the ERC721 standard.

**Thoughts**: Learned about why the ERC721 token standard requires the ERC165 token standard. Luckily it's not rocket science. The ERC165 token standard interface only has one function `supportsInterface`. I quote:

> The ERC165 Standard is just a way of checking if your contract’s fingerprints match the fingerprint of any given interface.
  
 **Reference(s)**:
 * [Part 1](https://medium.com/coinmonks/jumping-into-solidity-the-erc721-standard-part-1-e25b67fc91f3)
 * [Part 2](https://medium.com/coinmonks/jumping-into-solidity-the-erc721-standard-part-2-383438734de5)
 * [Part 3](https://medium.com/coinmonks/jumping-into-solidity-the-erc721-standard-part-3-5f38e012248b)
 
 ### Day 57: September 13, 2018
 ##### Developing my own game on Ethereum

**Today's Progress**: Added psuedo random number generation function.

**Thoughts**: Added a pseudo-random number generator for calculating the starting stats for an Etherlander. I am not using it for the selection of etherlanders because I want that functionality to be as decentralized as possible.
  
 **Reference(s)**:
 * [Pseudo Random Number Generator](https://ethereum.stackexchange.com/questions/57282/any-pseudo-random-number-generator-that-can-generate-different-numbers-in-the-sa)
 
 ### Day 58: September 14, 2018
 ##### Developing my own game on Ethereum

**Today's Progress**: Continued reading article series about the ERC721 standard.

**Thoughts**: Learned about the Metadata and Enumerable extensions. Before reading the articles, I didn't even know what extensions meant in the context of Solidity development. It turns out you can extend your contract on these extensions on top of the already extended ERC721 token standard. This will provide you which some extra functions.
  
 **Reference(s)**:
 * [Part 4](https://medium.com/coinmonks/jumping-into-solidity-the-erc721-standard-part-4-ad21e3a5d9c)
 * [Part 5](https://medium.com/coinmonks/jumping-into-solidity-the-erc721-standard-part-5-3b91f39fc1ee)
 * [Part 6](https://medium.com/coinmonks/jumping-into-solidity-the-erc721-standard-part-6-7ea4af3366fd)
 * [Part 7](https://medium.com/coinmonks/jumping-into-solidity-the-erc721-standard-part-7-9aca1411375a)
 
 ### Day 59: September 15, 2018
 ##### Decentralized Applications course

**Today's Progress**: Enrolled in a new course given by Siraj Raval about Decentralized Applications.

**Thoughts**: Got a deeper understanding about how Ethereum works under the hood. Learned about the Ethereum Virual Machine (EVM) and that the Ethereum blockchain doesn't store Solidity doe but a low level language called EVM bytecode.

From now on I will switch between working on this course and working on Etherlanders.
  
 **Reference(s)**:
 * [The course](https://www.theschool.ai/courses/decentralized-application/)
 
 ### Day 60: September 16, 2018
 ##### Decentralized Applications course

**Today's Progress**: Learned about Whisper.

**Thoughts**: Whisper is an off chain communication protocol for DApps to communicate with each other. DApps can publish small amounts of information to each other for a certain amount of time. In general, think transactions, but without the eventual archival, any necessity of being bound to what is said or automated execution & state change.

Think about DApps that need to signal to each other in order to ultimately collaborate on a transaction.
  
 **Reference(s)**:
 * [The course](https://www.theschool.ai/courses/decentralized-application/)
 * [Whisper](https://github.com/ethereum/wiki/wiki/Whisper)
 
 ### Day 61: September 17, 2018
 ##### Decentralized Applications course

**Today's Progress**: Learned about Decentralized Games.

**Thoughts**: The Decentralized Applications has a chapter committed to 'Decentralized Games'. In this chapter: they explained how CryptoKitties works under the hood, showed examples of successful games already developed, and they talked about how to use Ethereum and the Unity3D game engine together.

This chapter also includes a midterm project so I am going to hand in the Etherlanders project when it is done, this provides a nice way of combining taking this course and working on Etherlanders.
  
 **Reference(s)**:
 * [The course](https://www.theschool.ai/courses/decentralized-application/)
 * [Cryptokitties](https://etherscan.io/address/0xda9c03dfd4d137f926c3cf6953cb951832eb08b2#code)
 
 ### Day 62: September 18, 2018
 ##### Decentralized Applications course

**Today's Progress**: Read articles about blockchain development best practices from Consensys.

**Thoughts**: Consensys also has a section dedicated to random number generation. This is great because I need to implement this in Etherlanders. It says that generating random numbers still is an area of active research so there is no best solution (yet).

> Current best-in-class solutions include Bitcoin block headers (verified through [http://btcrelay.org](http://btcrelay.org))
  
 **Reference(s)**:
 * [The course](https://www.theschool.ai/courses/decentralized-application/)
 * [Consensys](https://consensys.github.io/smart-contract-best-practices/recommendations/#remember-that-on-chain-data-is-public)
 * [RANDAO](https://github.com/randao/randao)
 
 ### Day 63: September 19, 2018
 ##### Decentralized Applications course

**Today's Progress**: Read about Ethereum best practices.

**Thoughts**: Read about the locking pragmas to a specific version. If you don't use the `^` sign before the version number in your smart contract, it will always use that specific version.

Also, read about the best practices of starting all your event names with 'Log' for example `LogNewEtherlander` this prevents confusion with the function called `newEtherlander()` although you now have to use `emit` to emit an event it still is a good practice.
  
 **Reference(s)**:
 * [The course](https://www.theschool.ai/courses/decentralized-application/)
 * [Differentiate functions and events](https://consensys.github.io/smart-contract-best-practices/recommendations/#differentiate-functions-and-events)
 * [Lock pragmas to specific compiler version](https://consensys.github.io/smart-contract-best-practices/recommendations/#lock-pragmas-to-specific-compiler-version)
 
 ### Day 64: September 20, 2018
 ##### Decentralized Applications course

**Today's Progress**: Finished the course (video material).

**Thoughts**: Although I didn't really switch between following this course and working on Etherlanders I learned a lot by following this course. Most of the work assignments are covering subjects I already learned so I am not planning to finish these assignments.

From now on I will work on Etherlanders project again. The main goal from now on to the end of this challenge will be to release a working alpha version of the game at the end of this challenge.
  
 **Reference(s)**:
 * [The course](https://www.theschool.ai/courses/decentralized-application/)
 
 ### Day 65: September 21, 2018
 ##### Developing my own game on Ethereum

**Today's Progress**: Started coding front-end logic.

**Thoughts**: I used the same boilerplate code that I used for building the Election-DAPP I made some time ago. I wanted to make this website with Vue but I think it is best to only focus on learning more about blockchain because otherwise, the project will take too much time.
 
 **Link(s) to work**:
 * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)
 
 ### Day 66: September 22, 2018
 ##### Developing my own game on Ethereum

**Today's Progress**: Implented frontend template.

**Thoughts**: After some web surfing, I found an awesome looking website template. I changed the content and linked back to the white-paper. I was struggling a bit when I had to merge the JavaScript of the template and my web3 boilerplate. After some trial and error, everything works as expected.
  
 **Reference(s)**:
 * [Website template](https://www.styleshout.com/templates/preview/Count10/index-static.html)
 
 **Link(s) to work**:
 * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)
 
  ### Day 67: September 23, 2018
 ##### Developing my own game on Ethereum

**Today's Progress**: Website is now live!

**Thoughts**: I had to disable some of the web3 javascript code because the smart contract isn't deployed to any public blockchain yet. 
 
**Link(s) to work**:
* [Website](https://etherlanders.learnandbelieve.nl/)

 ### Day 68: September 24, 2018
 ##### Developing my own game on Ethereum

**Today's Progress**: Improved smart contract logic.

**Thoughts**: After analyzing the code base, I found out that it is very inefficient to have a 'buyPack' and 'openPack' function. In the scenario of 2 functions, you would have to pay 2 times to open only 1 pack. So I merged the 2 functions. The function is now called 'buyPacks'.

Second I removed the categories. Instead of a category an etherlander now has a skin which will determine his looks.
 
 **Link(s) to work**:
 * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)
 
 ### Day 69: September 25, 2018
 ##### Developing my own game on Ethereum

**Today's Progress**: Wrote unit test for the newly added contract logic.

**Thoughts**: I changed the 'buyPacks' function to 'buyPack'. I did this because otherwise, the function could become very computationally heavy (i.e. cost a lot of Gas). As of this moment, the newly added logic still isn't passing 100% on the unit test. There is an "invalid opcode" error when the "return by id" functions are called. Tomorrow I will look try to resolve these errors.
 
 **Link(s) to work**:
 * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)
 
 ### Day 70: September 26, 2018
 ##### Developing my own game on Ethereum

**Today's Progress**: Wrote unit test for buying packs with ether.

**Thoughts**: I found out there is no need for a getter function like `getEtherlanderById`. If you declare an array public in solidity, you automatically get getter and setter functions for free.

After some trial and error, I found out where the "invalid opcode" error came from. I called a getter function with an index that didn't exist. As of now I still don't know why my `add` function doesn't return the right id.

At last, I added a unit test for testing sending ether to the `buyPack` function. This is possible by adding the metadata `to: this.contract.address` and `value: 10000` to the transaction request.
 
 **Link(s) to work**:
 * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)
 
 ### Day 71: September 27, 2018
 ##### Developing my own game on Ethereum

**Today's Progress**: Resolved invalid opcode error / Optimized website with Lighthouse

**Thoughts**: After a lot of trial and error I found out that the ids my function returned were incorrect. Instead of subtracting 1 from the result of the `.push` function I now subtract 2. Still, this behavior is very weird because `.push` should return the new length of the array, so after adding an item subtracting 1 should give me the right index.

 **Reference(s)**:
 * [Lighthouse](https://developers.google.com/web/tools/lighthouse/)

 **Link(s) to work**:
 * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)
 
 ### Day 72: September 28, 2018
 ##### Developing my own game on Ethereum

**Today's Progress**: Enhanced unit tests 

**Thoughts**: I added tests for checking the `LogNewEtherlander` event and the `attacks` array from the `Etherlanders` struct. Checking the event was a piece of cake but for some reason, the default `etherlanders` getter function doesn't return arrays.

To get around this I wrote a new `external view` function that takes one argument, an etherlanderId. This function then returns the attacks array for the given etherlanderId.

 **Link(s) to work**:
 * [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)
 
### Day 73: September 29, 2018
##### Developing my own game on Ethereum

**Today's Progress**: Deepened my knowledge of Solidity.

**Thoughts**: Today I found a really good tutorial series on youtube about learning Solidity. Although I already know all the basics it still is very interesting to follow. The series really explains why certain things work the way they do. I learned about the difference between `require, assert and revert` before this tutorial I didn't even know about `revert`.

This tutorial also shows how to use Remix the Ethereum (online) IDE. It is a great tool for debugging your smart contracts.

**Reference(s)**:
* [Solidity turtorial](https://www.youtube.com/playlist?list=PL16WqdAj66SCOdL6XIFbke-XQg2GW_Avg)

### Day 74: September 30, 2018
##### Developing my own game on Ethereum

**Today's Progress**: Deepened my knowledge of Solidity.

**Thoughts**: Learned about fallback functions in Solidity. Apparently, when you don't provide a function name it is considered a fallback function. This function will be called when a sender doesn't specify a function to call. Sometimes this is used for a core payment functionality or to return send ether to the sender.

Next I learned about how strings are actually an array of integers. And that these integers are ASCII values representing the characters inside of the strings.

At last, I learned about the existence of fixed point integers. This data-type actually isn't implemented yet but the `solc` compiler already knows about them. The easiest way of explaining them is a `float` but with a **fixed** point.

**Reference(s)**:
* [Solidity turtorial](https://www.youtube.com/playlist?list=PL16WqdAj66SCOdL6XIFbke-XQg2GW_Avg)

### Day 75: October 1, 2018
##### Developing my own game on Ethereum

**Today's Progress**: Found dashboard template.

**Thoughts**: I searched for a dashboard template and found the OpenSource CoolAdmin template. My idea is that I will tweak this admin dashboard a bit so it looks like a great interface for our web application. I will also move pure HTML to PHP so I could modularize all the main components of the template.

**Reference(s)**:
* [CoolAdmin template](https://github.com/puikinsh/CoolAdmin)

### Day 76: October 2, 2018
##### Developing my own game on Ethereum

**Today's Progress**: Update user dashboard.

**Thoughts**: The dashboard template I found yesterday can be used as the users home page. After some searching on the web, I also found a free creature image pack. This pack will be the perfect starting point for etherlander designs.

**Reference(s)**:
* [CoolAdmin template](https://github.com/puikinsh/CoolAdmin)
* [Creature pack](https://pipoya.itch.io/free-rpg-monster-pack)

**Link(s) to work**:
* [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)

### Day 77: October 3, 2018
##### Developing my own game on Ethereum

**Today's Progress**: Modularized user dashboard.

**Thoughts**: The different modules like the header and navbar moved to sperate files that can be included where needed. I am still struggling a bit with the hyperlink-references because I will be loading the navbar module on multiple pages. This means that the path to other web pages will have to be referenced by their full path. The problem is that my dev environment isn't the same as the production environment.

**Link(s) to work**:
* [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)

### Day 78: October 4, 2018
##### Developing my own game on Ethereum

**Today's Progress**: Fixed hyperlinks-reference problem.

**Thoughts**: I added a configuration file which can be used to specify the websites URL. This solves the hyperlink problem because I can change the configuration file depending on the environment.

**Link(s) to work**:
* [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)

### Day 79: October 5, 2018
##### Developing my own game on Ethereum

**Today's Progress**: Changed directory structure / Started moving to OOP.

**Thoughts**: I changed to the directory structure, it now is better logically ordered. It's a real challenge to make the structure as logical as possible. This is because I am combining a PHP project with the Truffle Framework. I don't want to include a framework like Laravel because combining that with Truffle will be a real challenge.

**Link(s) to work**:
* [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)

### Day 80: October 6, 2018
##### Developing my own game on Ethereum

**Today's Progress**: Written a `ComponentLoader` and `Config` class.

**Thoughts**: With my `Config` class I can readout the `config.ini` file with dot notation: `$config->get('paths.url')`. With my `ComponentLoader` class I don't have to include the full path to the resources directory, I can just do: `$components->include('header.mobile')`. I think this makes to code way cleaner and easier to read.

**Link(s) to work**:
* [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)

### Day 81: October 7, 2018
##### Developing my own game on Ethereum

**Today's Progress**: Added `web3` to admin dashboard.

**Thoughts**: I wanted to add web3 to the admin dashboard so I could test displaying all owned etherlanders. So first I will need to seed some etherlanders to on account. But for some reason, MetaMask gives an error when I want to call the `buyPack` function. After some struggling, I decided to focus on something else. Instead of testing the display functionality I added a loader to the page. This loader has the option to display errors to the screen. Right now the web-page provides the user with a user-friendly error when MetaMask isn't installed.

**Link(s) to work**:
* [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)

### Day 82: October 8, 2018
##### Developing my own game on Ethereum

**Today's Progress**: Made a planning for finishing an alpha version of the game at the end of this challenge.

**Thoughts**: I think it would be great to have a playable version of the game at the end of this challenge. After trying to make the planning I saw it would be way to much work to finish everything in time. So I decided to ignore the battling and trading aspects for now. This allows me to purely focus on the core functionality, buying etherlanders.

**Link(s) to work**:
* [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)

### Day 83: October 9, 2018
##### Developing my own game on Ethereum

**Today's Progress**: Finished storyline / Create map.

**Thoughts**: After finishing the storyline I wanted to draw a map. So first I googled around a bit, then I found out about an open source map generator. After some tweaking with the settings, I now have a perfect map to use for the Etherlanders storyline.

**Reference(s)**:
* [Fantasy map generator](https://azgaar.github.io/Fantasy-Map-Generator/)

**Link(s) to work**:
* [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)

### Day 84: October 10, 2018
##### Developing my own game on Ethereum

**Today's Progress**: Added login option to homepage / added a help section.

**Thoughts**: For now when someone visits the `/login` page they will automatically be logged in. Later on, you will have an option to login/register. Not everyone will have Metamask installed yet, which is needed for viewing your dashboard. So after logging in you will be redirected to the homepage.

Because education about blockchain is our main goal here, I will have to write tutorials on how users can start engaging with the DAPP. These resources will, later on, be available from the home screen.

**Link(s) to work**:
* [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)

### Day 85: October 11, 2018
##### Developing my own game on Ethereum

**Today's Progress**: Improved help section.

**Thoughts**: I improved the help section of the page by removing unnecessary content. A problem arose when I wanted to refer to the help section by URL. The `help` section is part of the homepage and invisible at the start. After some trial and error, I added an `if statement` in PHP the check the URL for GET parameter named `help`. If so it will show the `help` from the start.

**Link(s) to work**:
* [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)

### Day 86: October 12, 2018

**Today's Progress**: Followed tutorial about Assembly within Solidity.

**Thoughts**: At the moment I have a huge headache, but this will not stop me from completing this challenge. It didn't seem a good idea to do anything with programming so I decided to continue the solidity tutorial.

I learned that can use both functional and instructional assembly within a smart contract. Although it does same GAS costs it's not used often because it is difficult to read/understand. Functional is used for very specific GAS expensive functions. Instructional assembly is actually (almost) never used because the difference in GAS cost, when compared to the functional way, is really really small.

**Reference(s)**:
* [Solidity turtorial](https://www.youtube.com/playlist?list=PL16WqdAj66SCOdL6XIFbke-XQg2GW_Avg)

### Day 87: October 13, 2018
##### Developing my own game on Ethereum

**Today's Progress**: Realised navbar functionality.

**Thoughts**: The search-bar was really easy to implement, just some javascript code that shows and hides certain cards. For the statistics, I created special HTML data attributes and a javascript function to provide these elements with content. The most interesting part was displaying the account information. For this, I moved from using a single string to a `User` object. When saving this to a `session variable` the object first needed to be serialized. Therefor I provided the `boostrap/app.php` file with some special logic for unserializing the serialized string.

**Link(s) to work**:
* [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)

### Day 88: October 14, 2018
##### Developing my own game on Ethereum

**Today's Progress**: Designed buy-packs page / fixed loader bug

**Thoughts**: The template I use automatically injects a loader into every page. It took me some searching but I removed the loader from the template. Second, I found a use for the "boss" images included in the icon pack. They can be used as card pack covers on the buy-packs page.

**Link(s) to work**:
* [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)

### Day 89 October 15, 2018
##### Developing my own game on Ethereum

**Today's Progress**: Designed database schema.

**Thoughts**: After designing the database schema I created the DDL script to build the database. I wasn't happy with this solution so I searched for a lightweight PHP migration library. Eventually, I found out about the Phnix migration library from the CakePHP framework.

I'm still struggling a bit with added Foreign Keys. But next to that I really like this library because they replaced the `up` and `down` functions with a `change` function that works both ways.

**Reference(s)**:
* [Phinx migrations](https://phinx.org)

**Link(s) to work**:
* [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)

### Day 90 October 16, 2018
##### Developing my own game on Ethereum

**Today's Progress**: Moved from .ini to .yml

**Thoughts**: I combined the Phnix yaml file with the default .ini file. And I also removed the config folder because there is no actual need for it. Next to that, I fixed the bug of added a foreign key with Phnix by changing the options parameter.

**Link(s) to work**:
* [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)

### Day 91 October 17, 2018
##### Developing my own game on Ethereum

**Today's Progress**: Found a lightweight and efficient alternative to Object-Relational Mapping for PHP.

**Thoughts**: Migration are now handled by Phnix and executing queries is handled by Lessql. Right now I implemented some basic logic to log in a user. Right now I am behind on schedule but I find it essential that database queries are correctly handled.

**Reference(s)**:
* [Lessql](http://lessql.net)

**Link(s) to work**:
* [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)

### Day 92 October 18, 2018
##### Developing my own game on Ethereum

**Today's Progress**: Started with implementing routing.

**Thoughts**: Started with implementing routing because I want to separate the actual HTML pages from all the CSS, JS, images, etc. I still encountered some problems with including some helper function, but I fixed that by defining them as static function inside a class.

**Link(s) to work**:
* [Etherlanders repo](https://github.com/RoyVoetman/Etherlanders/)

### Day 93 October 19, 2018
##### Developing my own game on Ethereum

**Today's Progress**: Separated smart contracts from the actual web application.

**Thoughts**: Because the smart contracts and the web application actually are sperate applications I moved them into two sperate repo's. A problem arises when wanting to include the ABI files generated by smart contract repo into the web application repo. But when the smart contracts are deployed to the Ethereum blockchain these ABI files won't change that often anymore. So, for now, they will just exist in both repo's.

**Link(s) to work**:
* [Etherlanders smart contracts repo](https://github.com/RoyVoetman/Etherlanders-smart-contracts)
* [Etherlanders web application repo](https://github.com/RoyVoetman/Etherlanders-webapplication)

### Day 94 October 20, 2018
##### Developing my own game on Ethereum

**Today's Progress**: Finished routing in the web application.

**Thoughts**: With my current progress I won't be able to finish the application at the end of the challenge. But this shouldn't be a problem. What I wanted to achieve with this challenge is to learn more about blockchain. In my opinion, I learned a lot! I could always finish the game later after the challenge is finished.

**Link(s) to work**:
* [Etherlanders web application repo](https://github.com/RoyVoetman/Etherlanders-webapplication)

> Missed October 21 to 24 due to a college trip

### Day 95 October 25, 2018
##### Developing my own game on Ethereum

**Today's Progress**: Found out about the Singleton design pattern.

**Thoughts**: Today I finally found the solution to the problem I had with preventing the need for instantiating a class multiple times. With a Singleton, you save an instance of the class as a static property. Only if the property is empty the class gets instantiated. This prevents the class from being instantiated multiple times.

**Reference(s)**:
* [Singleton](https://medium.com/@NahidulHasan/laravel-ioc-container-why-we-need-it-and-how-it-works-a603d4cef10f#4ddf)

**Link(s) to work**:
* [Etherlanders web application repo](https://github.com/RoyVoetman/Etherlanders-webapplication)

### Day 96 October 26, 2018

**Today's Progress**: Followed tutorials about Solidity.

**Thoughts**: I decided to deepen my knowledge of Solidity the best I can in the last few days. When I look back at the development of the web application it is mostly PHP. Working on that application doesn't really deepen my knowledge about blockchain technology.  

**Reference(s)**:
* [Randomness and Gambling](https://www.youtube.com/watch?v=3wY5PRliphE)
* [Time Based Events](https://www.youtube.com/watch?v=HGw-yalqdgs)

### Day 97 October 27, 2018

**Today's Progress**: Followed tutorials about Solidity.

**Thoughts**: Today I learn about why nested and dynamic arrays don't always work. It has to do with how Solidity stores the array. Storage, for example, works just fine but Memory, on the other hand, will throw an error. Right now an array in memory is stored back to back to back to back, in other words, it doesn't use reference pointers. This is a problem when you want your array to be dynamic.

There are ways to get around this but it requires you to write it in Assembly. With assembly, you can do your own memeory allocation and kinda make your own data-structure but this is really a pain in the ass to write.

**Reference(s)**:
* [Truffle](https://www.youtube.com/watch?v=YcTSilIfih0)
* [Nested Arrays and Storage](https://www.youtube.com/watch?v=zkNHRJEuYQg)

### Day 98 October 28, 2018

**Today's Progress**: Followed tutorials about Solidity.

**Thoughts**: Learned about MultiSig Wallets and coding one yourself in Solidity. The function of a MultiSig Wallet is that multiple accounts own the wallet. So if one of the address is lost, you could still access the wallet. Another cool feature can be a to add a requirement that a transaction first needs to be accepted by 'X' amount of owners.

Next to that, I learned that you can return multiple values in Solidity. This is great because I had some struggles with that in the past.

**Reference(s)**:
* [MultiSig Wallet](https://www.youtube.com/watch?v=OwavQTuHoM8)
* [MultiSig Wallet 2](https://www.youtube.com/watch?v=23YLeX7mpbU)
* [Parameter Mapping and Multiple Return Values](https://www.youtube.com/watch?v=v3aoiTh-UVQ)

### Day 99 October 29, 2018

**Today's Progress**: Followed tutorials about Solidity.

**Thoughts**: Today I learned two new tools, solc, and web3j. Solc is the solidity compiler, previously I always compiled smart contracts with truffle. Web3j is a java library for integration with Ethereum clients. It is kinda like web3js but for java instead of JavaScript.

**Reference(s)**:
* [Java and Android library for integration with Ethereum clients](https://www.youtube.com/watch?v=kJ905hVbQ_E)

### Day 100 October 30, 2018

**Today's Progress**: Reflected on all that I have learned these 100 days.

**Thoughts**: Today I looked back at everything that I have learned in the past 100 days. I really learned a lot! It seems ages ago since I wrote my first smart contract within solidity with truffle. Overall I am glad I finished this challenge when I see what I have learned. Not only about blockchain but about programming in general as well.

**Reference(s)**:
* [100 days of blockchain code](https://github.com/RoyVoetman/100-days-of-blockchain-code)

