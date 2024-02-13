</p>

# Multithread Bitcoin Brute Force for Segwit addresses( also known as Bech32 )

This is a Node.js script that uses multiple worker processes to generate random private keys for Bitcoin Segwit addresses are also known as Bech32 wallets and check if they match any of the Segwit addresses are also known as Bech32 addresses in a file named `data.txt`

## For people without technical experience you can buy the compiled application for windows from here:

[https://www.buymeacoffee.com/aghostdev](https://www.buymeacoffee.com/aghostdev)Keep in mind that a Windows app won’t speed up searching or guarantee success.

## Requirements

- Node.js
- npm

## Installation

1. Clone this repository or download the code as a zip file and extract it.
2. Open a terminal or command prompt and navigate to the directory where the code is located.
3. Run `npm install` to install the required dependencies.

<h3 align="left">Support:</h3>
<p><a href="https://www.buymeacoffee.com/corvuscodex"> <img align="left" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="corvuscodex" /></a></p><br><br>

`<br><br>`
Donate: `<br>`
BTC: bc1qr2aj946n9su4pzmcy4qdew643q6e3lacr009az `<br>`
ETH: 0x7b68F10c7D3757E15A188f233F53EE237cd081E8
USDT: 0x7b68F10c7D3757E15A188f233F53EE237cd081E8
BNB: 0x7b68F10c7D3757E15A188f233F53EE237cd081E8

## Usage

1. Add the Bitcoin addresses you want to check against to a file named `data.txt`, with one address per line.
2. Run `node app.js` to start the script.
3. Pick verison, default is 1
4. The script will display the loop count for each worker process in real-time.
5. If a match is found, the wallet address and its private key will be saved to a file named `match.txt` and the script will exit.

> Support my work:`<br>`
> BTC: bc1qr2aj946n9su4pzmcy4qdew643q6e3lacr009az `<br>`
> ETH: 0x7b68F10c7D3757E15A188f233F53EE237cd081E8 `<br>`
> USDT: 0x7b68F10c7D3757E15A188f233F53EE237cd081E8 `<br>`
> BNB: 0x7b68F10c7D3757E15A188f233F53EE237cd081E8 `<br>`

## Support my work for month or year so i can continue to work on my projects:

https://www.buymeacoffee.com/aghostdev/membership

## Buy me some equipment:

https://www.buymeacoffee.com/aghostdev/wishlist

## Disclaimer

The code within this repository comes with no guarantee, the use of this code is your responsibility. I take NO responsibility and/or liability for how you choose to use any of the source code available here. By using any of the files available in this repository, you understand that you are AGREEING TO USE AT YOUR OWN RISK. Once again, ALL files available here are for EDUCATION and/or RESEARCH purposes ONLY. The chances of finding a match are extremely low and it is not recommended to use this script for any illegal or unethical activities.

MIT License

Copyright (c) 2023 Aghostdev

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
