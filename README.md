# spicetify-ready
Clone,Run the script and get a revamped spotify.

The most easy way to install spotify is from snap but spotify installed from snap won't work.
Apps installed from Snap cannot be modified so you need to follow these steps to get Spicetify working:

Uninstall Spotify in Snap or run command
```snap remove spotify```
Install Spotify using apt:
```curl -sS https://download.spotify.com/debian/pubkey_0D811D58.gpg | sudo apt-key add - ```
```echo "deb http://repository.spotify.com stable non-free" | sudo tee /etc/apt/sources.list.d/spotify.list```
```sudo apt-get update && sudo apt-get install spotify-client```
Or simply run the ```setup.sh``` to setup your spotify automatically.

To clone the repository:
```git clone https://github.com/Git-Ankitraj/spicetify-ready.git```
To setup:
```
cd spicetify-ready 
sudo chmod +x setup.sh
sudo ./setup.sh
```

You can customize your spicetify as per you wish, follow the steps in official spisetify repo:
https://github.com/khanhas/spicetify-cli.git
