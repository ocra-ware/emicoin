# Emicoin Token Design Summary

**Symbol**: EMI  
**Decimals**: 18  
**Networks**: Polygon, Ethereum

---

## 🎯 Purpose
Emicoin is a utility token created by Ocraware to support decentralized, community-driven finance. It is designed for:
- Peer-to-peer transactions
- Ecosystem participation
- DAO governance (future)
- Integration with third-party dApps and platforms

---

## 🔧 Supply and Minting
- Initial mint: 500,000 EMI (on both Ethereum and Polygon)
- Token is **mintable** by the contract owner
- Owner is intended to represent a DAO or controlled multisig in future

### Mint Function
The `mint(address to, uint256 amount)` function allows controlled supply expansion.

### Burn Function
The `burn(address from, uint256 amount)` allows supply deflation or removal of tokens by the owner.

---

## 🏗️ Architecture
- Built with OpenZeppelin ERC20 + Ownable contracts
- Same symbol and decimals across both chains
- No complex logic, no proxy, no fees, no tax

---

## 🌉 Bridging
Emicoin is designed for cross-chain functionality.

- Currently bridged via Polygon PoS bridge (in progress)
- Future support planned for LxLy infrastructure
- Token on both chains has matching metadata for compatibility

---

## 🔒 Security
- Verified source code on Etherscan and Polygonscan
- Built entirely with audited OpenZeppelin contracts
- Internal review completed

---

## 📎 Notes
- Emicoin has no presale or private allocation
- Emicoin is not a security or financial instrument

---

**The Emicoin Team**
