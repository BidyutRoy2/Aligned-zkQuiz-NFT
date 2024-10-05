<h1 align=center>Aligned zkQuiz NFT</h1>

## Add Holesky Testnet Metamask RPC 

Network Name - `Holesky Test Network`

Network URL - `https://rpc.holesky.ethpandaops.io/`

Chain ID - `17000`

Symbol - `ETH`

Explorer URL - `https://holesky.etherscan.io/`

## Or Add RPC From Explore : https://holesky.etherscan.io

## Claim Ethereum Holesky FAUCET (Use New or Burner Wallet)
- https://www.alchemy.com/faucets/ethereum-holesky
- https://cloud.google.com/application/web3/faucet/ethereum/holesky
- https://holesky-faucet.pk910.de

![Img1](https://github.com/user-attachments/assets/4e323dd3-cdee-44be-b62c-f18253da6446)

## Go To Github CodeSpace : https://github.com/codespaces
- Select Blank templates

## Install Rust - Past Command
```bash
source <(wget -O - https://raw.githubusercontent.com/BidyutRoy2/BidyutRoy2/refs/heads/main/installation/rust.sh)
```

## Install Foundry - Past Command
```bash
source <(wget -O - https://raw.githubusercontent.com/BidyutRoy2/BidyutRoy2/refs/heads/main/installation/foundry.sh)
```

## Install OpenSSL and pkg-config - Past Command
```bash
sudo apt update && sudo apt install pkg-config libssl-dev
```

## Import a New/Burner wallet Private Key - Past Command
```bash
[ -d ~/.aligned_keystore ] && rm -rf ~/.aligned_keystore && echo "Deleted existing directory ~/.aligned_keystore." ; mkdir -p ~/.aligned_keystore && cast wallet import ~/.aligned_keystore/keystore0 --interactive
```

## Clone Aligned Layer repo - Past Command
```bash
[ -d aligned_layer ] && rm -rf aligned_layer && echo "Deleted existing aligned_layer directory." ; git clone https://github.com/yetanotherco/aligned_layer.git && cd aligned_layer/examples/zkquiz
```

## Run this final command
```bash
make answer_quiz KEYSTORE_PATH=~/.aligned_keystore/keystore0
```
- In the last stage it will ask some questions, here is the answers

`Y` , `C` , `C` , `A` , `Y`
