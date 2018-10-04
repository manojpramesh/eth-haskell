## Eth-Haskell

Sample Learning project - Haskell REST service to interact with Ethereum blockhain.

#### Current features

1. Web server
2. Sample Handlers (Routes)
3. HTML Templates (Will be replaced with plain HTML/Haxe)

#### TODO
1. Connect to Ethereum
2. Connect to Database
3. Dockerize
4. Replace front-end with HTML/Haxe


### To build the project

1. install Stack 
	https://haskell-lang.org/get-started

2. Clone the repo

3. Install the `yesod` command line tool
	```
	stack install yesod-bin --install-ghc
	```
4. Build libraries
	```
	stack build
	```
5. Run
	```
	stack exec -- yesod devel
	```

### Add a new Handler

```
yesod add-handler
```