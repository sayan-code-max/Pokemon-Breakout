<!-- {
	"contracts": {
		"FungibleToken": {
			"source": "./contracts/FungibleToken.cdc",
			"aliases": {
				"emulator": "0xee82856bf20e2aa6",
				"testnet": "0x9a0766d93b6608b7"
			}
		},
		"NonFungibleToken": {
			"source": "./contracts/NonFungibleToken.cdc",
			"aliases": {
				"emulator": "0xf8d6e0586b0a20c7",
				"testnet": "0x631e88ae7f1d7c20"
			}
		},
		"MyNFT": {
			"source": "./contracts/MyNFT.cdc"
		},
		"BasicNFT": {
			"source": "./contracts/BasicNFT.cdc"
		},
		"FlowToken": {
			"source": "./contracts/FlowToken.cdc",
			"aliases": {
				"emulator": "0x0ae53cb6e3f42a79",
				"testnet": "0x7e60df042a9c0868"
			}
		},
		"NFTMarketplace": {
			"source": "./contracts/NFTMarketplace.cdc"
		}
	},
	"deployments": {
		"testnet": {
			"testnet-account": ["MyNFT","NFTMarketplace", "BasicNFT"]
		}
		
	},
	"networks": {
		"emulator": "127.0.0.1:3569",
		"mainnet": "access.mainnet.nodes.onflow.org:9000",
		"sandboxnet": "access.sandboxnet.nodes.onflow.org:9000",
		"testnet": "access.devnet.nodes.onflow.org:9000"
	},
	"accounts": {
		"emulator-account": {
			"address": "f8d6e0586b0a20c7",
			"key": "523a56348bc56af06c3eb9e5e826acfa93b03a485b1499a743ee4e048b167564"
		},
		"testnet-account": {
			"address": "0x9f690718478ff417",
			"key": "f563a33c0eaba33e2bf3560c7381e68dfed612993ba17e2146765f8710e35d54"
		}
	}
} -->
