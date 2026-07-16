1.sudo apt update && sudo apt upgrade -y 
2.curl --proto '=https' --tlsv1.2 -sSf 
https://sh.rustup.rs | sh 
3.source $HOME/.cargo/env 
4.rustc --version 
cargo --version 
5.echo 'source $HOME/.cargo/env' >> 
~/.bashrc 
6.source ~/.bashrc 
7.curl -sSL 
https://raw.githubusercontent.com/soundne sslabs/soundness-layer/main/soundnessup/ 
install | bash 
8.source ~/.bashrc 
9.soundnessup install 
soundnessup update 
10.soundness-cli generate-key --name 
my-key 
11.Importing a Key Pair To import an 
existing key pair from a mnemonic 
phrase: 
soundness-cli import-key --name my-key 
12.Listing Key Pairs To view all stored 
key pairs and their associated public 
keys: 
soundness-cli list-keys 
13.Exporting Key Mnemonic To export the mnemonic phrase for a stored key 
pair: 
soundness-cli export-key --name my-key
