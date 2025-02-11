
## AI Minter

This is a simple AI minter example built on top of **Next.js 14** using some of [@mintbase-js](https://github.com/Mintbase/mintbase-js) packages:

- [@mintbase.js/sdk](https://github.com/Mintbase/mintbase-js/tree/beta/packages/sdk): to use the execute call when minting

- [@mintbase.js/react](https://github.com/Mintbase/mintbase-js/tree/beta/packages/react) to provide the wallet connection

- [@mintbase.js/storage](https://github.com/Mintbase/mintbase-js/tree/beta/packages/sdk): to upload the images to Arweave

**DEMO:** https://ai-minter.mintbase.xyz/

### Setup
on the file *config/setup.ts* you have the object

```ts
export const MintbaseWalletSetup  = {
	contractAddress:  "test122212.mintspace2.testnet",
	network:  "testnet",
};
```
where contractAddress is the address of a store that you are a minter.
if you dont have a store you can [deploy a new contract](https://www.mintbase.xyz/launchpad/contracts/0) on our launchpad

after that you can run
```
pnpm install
```
and 

```
pnpm dev
```


## Extending

This project is setup using Next.js + @mintbase/js +  shadcn ui + react hook form
You can use this project as a reference to build your own, and use or remove any library you think it would suit your needs.



## Get in touch

- Support: [Join the Telegram](https://tg.me/mintdev)
- Twitter: [@mintbase](https://twitter.com/mintbase)