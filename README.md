# Vanity-Alaya | Alaya地址生成器

Browser-based Alaya vanity address generator

Just type [`https://vanity-alaya.github.io/`](https://vanity-alaya.github.io/) to use it ⚡️

## What's a vanity address? | 什么是Alaya地址生成器?

A vanity address is an address which part of it is chosen by yourself, making it look less random.

Examples: `atp1000000000000000000000000000000000abcde`, or `atp1888888888888888888888888888888888abcde`

## Usage | 使用

First of all, visit [`https://vanity-alaya.github.io/`](https://vanity-alaya.github.io/)

Enter as short prefix/suffix of your choice at the bottom of the page, and click ‘generate’ to start. Your browser will
generate lots of random addresses until one matches your input.

Once an address is found, you can reveal the private key, or click the 'save' button to download a password-encrypted keystore file.

You can increase the number of working threads to reach higher speeds, or decrease it if you computer struggles.

## Security | 安全

As explained above, everything is computed only in your browser. Nothing ever leaves your machine, or even your browser tab.
There is no database, no server-side code. Everything vanishes when you close your tab.

**Vanity-Alaya cannot and will never store your private key**, and if you don't trust it, you have 2 ways to ensure your key remains private:

- Once the web page is loaded, you can turn off the internet and continue playing, it will work seamlessly
- The code is 100% open source and available on Github. You can review it as much as you want before using it

Vanity-Alaya uses a cryptographically secure pseudorandom number generator (CSPRNG) to generate addresses.

## Performance | 性能

For some reason, the performance of Vanity-Alaya can vary a lot from a browser to another. 
Currently, Chrome provides the best results.

Using Vanity-Alaya on your phone or tablet will work, but don't expect to reach the speed of a good old computer.

## Compatibility | 兼容性


T100% compatible with ATON.


## Build Vanity-Alaya from source | 编译

The Travis CI bot 🤖 is in charge of building and deploying Vanity-Alaya to Github pages, but you can make your own build
from source is you want

```sh
git clone https://github.com/vanity-alaya/vanity-alaya.git
cd vanity-alaya
npm i
npm run build
```

## 赏杯奶茶

`atp100050lk4a9dfuylpmjkk2waf5yza4gwnhtuv2l`
