download the miner

```bash
wget https://cdn.nocturne.offchain.club/releases/v1.1.0/nocturne-miner-linux-x64.tar.gz
```

extract the downloaded file

```bash
tar xvf https://cdn.nocturne.offchain.club/releases/v1.1.0/nocturne-miner-linux-x64.tar.gz
```

start a screen (or tmux)

```bash
screen
```

run the miner

```bash
./nocturne-miner
```
follow the instructions on screen. when prompted for number of wallets --> take 200 or so. it doesn't matter if it's too much, it will just use what it needs.

when it prompts for the amount of threads, just go for the max amount it proposes.

wait a bit and confirm the miner is running okay.

exit your screen session by hitting
- 'ctrl' + 'a'
- then 'd' (no ctrl)
This detaches your screen session — the process keeps running in the background.
(if you're using tmux, it's very similar but just ctrl+b, then d)

then, do:
```bash
cat settings.json
```

this will output your settings.json that the miner created - this includes your seed phrase. store this somewhere securely.
