---
description: >-
  Emerald is a testing environment and framework that eases the development of
  decentralized applications on the Ethereum Classic blockchain.
---

# Emerald

**GitHub** [https://github.com/ETCDEVTeam/emerald](https://github.com/ETCDEVTeam/emerald)

Emerald has similar characteristics to Truffle Framework, however, integrates the tools of the Emerald Platform and more.

## Dependencies

* ​[homebrew](https://brew.sh/) \(for macOS users\)
* ​[nodenv](https://github.com/nodenv/nodenv)
* [node-build](https://github.com/nodenv/node-build#readme)

{% hint style="info" %}
If you have node already installed, then we recommend uninstalling node and npm before installing nodenv.  
{% endhint %}

Install nodenv and node-build using homebrew. 

```text
$ brew install nodenv
$ brew install node-build
```

Confirm nodenv and node-build are installed

```text
$ nodenv -v
nodenv 1.1.2
$ node-build --version
node-build 3.0.18
```

Install _stable_ node version using `nodenv install <version>` and make global using `nodenv global 8.11.1`

```text
$ nodenv install 8.11.1
$ nodenv global 8.11.1
```

Confirm node directory. 

```text
$ which node
/Users/JohnSmith/.nodenv/shims/node
```

## Install

Download Emerald from the project repo [https://github.com/ETCDEVTeam/emerald](https://github.com/ETCDEVTeam/emerald) or `git clone`

```text
$ git clone https://github.com/ETCDEVTeam/emerald
```

Within the working directory run 

```text
$ npm link
```

This process may take a few minutes. When it's done, Emerald will be installed globally. Open a new terminal window and run `emerald -h` to view commands and options.

```text
$ emerald -h

   emerald 0.0.1 

   USAGE

     emerald <command> [options]

   COMMANDS

     new                 Create a new project               
     wallet              Boot Emerald Wallet                
     explorer            Boot Explorer                      
     testrpc             Run testnet for ethereum classic   
     deploy              Deploy solidity to network         
     help <command>      Display help for a specific command

   GLOBAL OPTIONS

     -h, --help         Display help                                      
     -V, --version      Display version                                   
     --no-color         Disable colors                                    
     --quiet            Quiet mode - only displays warn and error messages
     -v, --verbose      Verbose mode - will also output debug messages    
```

## Usage


