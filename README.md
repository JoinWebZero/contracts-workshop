This workshop aims to introduce you to ink! &mdash; the native smart contracting language for the Polkadot ecosystem &mdash; by completing a series of quests.

Use this repository for installation instructions and to submit your proof of quests.
To submit your proof of quests, simply clone this repo and make a PR to the `submissions` folder containing details on the quests you've completed including screenshots.

Your workshop facilitator will provide you with a feedback form where you will need to provide a link to your submission PR to be eligible for quest rewards.

## Setup your environment

**Step 1: Make sure you have Rust installed on your machine**

Run: 

```bash
curl https://sh.rustup.rs -sSf | sh
```

Or visit for more details: https://doc.rust-lang.org/cargo/getting-started/installation.html

**Step 2: Install cargo-contract**

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
