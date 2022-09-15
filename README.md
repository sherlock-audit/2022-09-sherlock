# Sherlock contest details

- 15,000 USDC main award pot
- Join [Sherlock Discord](https://discord.gg/MABEWyASkp)
- Submit findings using the issue page in your private contest repo (label issues as med or high)
- [Read for more details](https://docs.sherlock.xyz/audits/watsons)
- Starts September 19, 2022 15:00 UTC
- Ends September 22, 2022 15:00 UTC

# Resources

- [Sherlock Docs](https://docs.sherlock.xyz/)
- [Recent Integration Post-Mortem](https://mirror.xyz/0xE400820f3D60d77a3EC8018d44366ed0d334f93C/LOZF1YBcH1eBdxlC6HP223cAMeTpNgQ-Kc4EjQuxmGA)
- [Sherlock V2 Core @ 355c70](https://github.com/sherlock-protocol/sherlock-v2-core/tree/355c70df23aa9aa7d46567c9540a6d15be93fcabrl)
- [Strategy README](https://github.com/sherlock-protocol/sherlock-v2-core/blob/355c70df23aa9aa7d46567c9540a6d15be93fcab/STRATEGY.md)
- [ToB Audit](https://github.com/sherlock-protocol/sherlock-v2-core/blob/main/audits/Sherlock%20-%20Trail%20of%20Bits%20Fix%20Review%20June%202022.pdf)
- [TrueFi Mainnet Contracts](https://github.com/trusttoken/contracts-pre22/tree/8c8d0cb12ace749b7eab8452b53da3f8c080a81a)
- [Euler Contracts](https://github.com/euler-xyz/euler-contracts)

# Audit scope

The focus of this audit is on any potential losses in Sherlock V2 related to the integration with TrueFi or Euler.

- `contracts/EulerStrategy.sol`
- `contracts/TrueFiStrategy.sol`

# About Sherlock

> source [Sherlock Docs](https://docs.sherlock.xyz/faq)

Sherlock is an audit marketplace and smart contract coverage protocol built on the Ethereum blockchain. Sherlock works to protect Decentralized Finance (DeFi) users from smart contract exploits with security reviews from top auditors backed by smart contract coverage on the audited contracts.

Most audit firms rely on their reputation to convince protocol teams to use them. This is a poor way to guarantee incentive alignment. Sherlock provides something far more valuable than reputation: millions of dollars. If a contract that is audited and covered by Sherlock gets exploited, then Sherlock's staking pools can lose millions of dollars. This is a much stronger incentive to do a good job vs. maintaining an amorphous reputation across thousand of audits and dozens of individual auditors.
