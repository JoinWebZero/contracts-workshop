![](./assets/blockspace-logo.png)

This workshop aims to introduce you to [ink!](https://use.ink/), the native smart contracting language for the [Polkadot](https://polkadot.network/) ecosystem, by completing a series of hands-on quests.
Use this repository to refer to installation instructions and to submit your proof of quests.


> 🔎 To submit your proof of quest, simply clone this repo and make a PR to the `submissions` folder titled `Quest submission: {your name,} {date}` containing a short summary of the quests you've completed. Include screenshots if relevant and a reviewer will verify your submission.

Your workshop facilitator will provide you with a feedback form where, once you provide some feebdack, you can provide a link to your submission PR to be eligible for quest rewards. 😎

## 📃 Workshop link

https://hackmd.io/@webzero/contracts-workshop

## 🧑‍💻 Setup your environment

**Step 1: Make sure you have Rust installed on your machine 🦀**

Run: 

```bash
curl https://sh.rustup.rs -sSf | sh
```

Or visit for more details: https://doc.rust-lang.org/cargo/getting-started/installation.html

**Step 2: Install cargo-contract 🪶**

Check that you're properly setup:

```bash
rustup show && cargo contract --help
```

example output:

```bash
Default host: aarch64-apple-darwin
rustup home:  /Users/salansky/.rustup

stable-aarch64-apple-darwin (default)
rustc 1.76.0 (07dca489a 2024-02-04)
Utilities to develop Wasm smart contracts

Usage: cargo contract <COMMAND>

Commands:
  new          Setup and create a new smart contract project
  build        Compiles the contract, generates metadata, bundles both together in a `<name>.contract` file
  check        Check that the code builds as Wasm; does not output any `<name>.contract` artifact to the `target/` directory
  upload       Upload contract code
  instantiate  Instantiate a contract
  call         Call a contract
  encode       Encodes a contracts input calls and their arguments
  decode       Decodes a contracts input or output data (supplied in hex-encoding)
  remove       Remove contract code
  info         Display information about a contract
  help         Print this message or the help of the given subcommand(s)

Options:
  -h, --help     Print help
  -V, --version  Print version
```

Now you're ready to get hacking ! 🚀
