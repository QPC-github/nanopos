# nanopos

A simple :zap: Lightning point-of-sale system with a clean & minimal web UI, based on [Lightning Charge](https://github.com/ElementsProject/lightning-charge).

Ideal for places selling fixed-price items (like coffee shops, falafel stands or barber shop), but also has an option for billing custom amounts.

Small codebase (~60 server-side LoC + ~70 client-side LoC), great starting point for developing your own Lightning Charge apps!

## Setup

```bash
$ git clone https://github.com/shesek/nanopos && cd nanopos
$ npm install

$ cp items.yaml.example items.yaml # edit to set your items
$ cp env.example .env # edit to set configuration options (all optional except for CHARGE_TOKEN)

$ npm start
```

## Screenshots

<img src="https://i.imgur.com/puslYKb.png" width="31%"></img>
<img src="https://i.imgur.com/kScuEjG.png" width="31%"></img>
<img src="https://i.imgur.com/qyGz4ey.png" width="31%"></img>

## License

MIT