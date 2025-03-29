# COMMAND 
sudo apt update && sudo apt upgrade -y
git clone https://github.com/soundnesslabs/soundness-layer.git
cd soundness-layer/soundness-cli
cargo install --path .
#Generate a Key Pair 
soundness-cli generate-key --name my-key
#your public keys by running the following command:
soundness-cli list-keys
#To export the mnemonic phrase for a stored key pair
soundness-cli export-key --name my-key
![image](https://github.com/user-attachments/assets/4ee90aea-82f7-4ebc-aed7-449e12742174)

