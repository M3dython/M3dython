<h1 align="center">Hi there, I'm M3dython 👋</h1>

<p align="center">
  <img src="[https://avatars.githubusercontent.com/u/68754219?s=96&v=4](https://avatars.githubusercontent.com/u/68754219?s=96&v=4)" width="150" height="150" style="border-radius: 50%;" alt="M3dython Profile">
</p>

<h3 align="center">
  Security Researcher | Smart Contract Auditor
</h3>

<p align="center">
  <a href="https://m3dython.com"><strong>🌐 m3dython.com</strong></a>
</p>

<p align="center">
  <em>I don't just hunt bugs; I secure Protocol Solvency. Specializing in advanced business logic exploits and economic attack vectors.</em>
</p>

---

### 👨‍💻 About Me

I'm **M3dython**, a specialized Blockchain Security Researcher focused on DeFi protocol architecture. I actively compete in top-tier audit contests like **Sherlock**, where I've earned recognition for identifying High/Critical vulnerabilities in complex financial logic.

My mission is to help projects scale securely. I bridge the gap between raw code and business logic to prevent treasury-draining exploits.

* 🔭 **Focus:** Advanced smart contract security patterns & auditing.
* 🌱 **Learning:** Solidity Fuzzing (Foundry/Echidna) and Formal Verification.
* 🛡️ **Services:** Available for private audits and consultation.
* ⚡ **Fun fact:** I find uncovering subtle logical flaws in Web3 protocols incredibly rewarding.

---

### 📊 Sherlock Stats

<p align="center">
  <a href="https://audits.sherlock.xyz/watson/m3dython">
    <img src="https://img.shields.io/badge/High%20Findings-8-red?style=for-the-badge" alt="High Findings">
    <img src="https://img.shields.io/badge/Medium%20Findings-4-orange?style=for-the-badge" alt="Medium Findings">
    <img src="https://img.shields.io/badge/Total%20Earnings-$3.33K-green?style=for-the-badge" alt="Total Earnings">
    <img src="https://img.shields.io/badge/All%20Time%20Rank-%231003-blue?style=for-the-badge" alt="All Time Rank">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Payouts-10x-purple?style=flat-square" alt="Payouts">
  <img src="https://img.shields.io/badge/Top%2010-3x-gold?style=flat-square" alt="Top 10">
  <img src="https://img.shields.io/badge/Top%2025-5x-silver?style=flat-square" alt="Top 25">
  <img src="https://img.shields.io/badge/Top%2050-9x-bronze?style=flat-square" alt="Top 50">
</p>

---

### 📬 Connect & Socials

<p align="center">
  <a href="https://m3dython.com"><img src="https://img.shields.io/badge/Portfolio-m3dython.com-blue?style=for-the-badge&logo=firefox" alt="Website"></a>
  <a href="https://twitter.com/m3dython"><img src="https://img.shields.io/badge/Twitter-@m3dython-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"></a>
  <a href="https://www.linkedin.com/in/0samalves/"><img src="https://img.shields.io/badge/LinkedIn-Sam%20Alves-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:m3dython@gmail.com"><img src="https://img.shields.io/badge/Email-Contact%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### 🛠️ Languages & Tools

<p align="center">
  <img src="https://skillicons.dev/icons?i=solidity,python,js,ts,rust,foundry,vscode,git,linux&perline=10" />
</p>

---

### 🏆 Audit Track Record

**Primary Platform:** [Sherlock Profile](https://audits.sherlock.xyz/watson/m3dython)

| Contest | Findings | Earnings | Rank |
| :--- | :---: | :---: | :---: |
| **Privacy Cash (Nov '25)** | - | 9.52 USDC | **#49** |
| **Saffron Fixed Income Vaults (Oct '25)** | - | 13.77 USDC | **#50** |
| **3Jane (Oct '25)** | - | 77.00 USDC | **#18** |
| **Yield Basis (Aug '25)** | 1 | 69.47 USDC | **#10** |
| **DeBank (Jul '25)** | - | 465.45 USDC | **#7** |
| **DODO Cross-Chain DEX (Jun '25)** | 1 | 75.65 USDC | **#39** |
| **LEND (May '25)** | 5 | 41.26 USDC | **#52** |
| **Burve (Apr '25)** | 3 | 2,509.74 USDC | **#8** |
| **PinLink RWA (Mar '25)** | - | 19.47 USDC | **#39** |
| **Yieldoor (Feb '25)** | 2 | 48.21 USDC | **#15** |

<br>

### 🔍 Detailed Findings Breakdown

<details>
<summary><strong>📂 Click to expand specific vulnerability details</strong></summary>

#### Yield Basis (Aug '25)
* **Finding:** Admin will brick gauge controller configuration for the protocol.

#### DODO Cross-Chain DEX (Jun '25)
* **Finding:** Any External Actor will Steal Approved ZRC20 Tokens from `GatewayTransferNative` Contract.

#### LEND Protocol (May '25)
* **Finding 1:** CrossChainRouter uses incorrect collateral/token data during cross-chain liquidations, disrupting repayment logic.
* **Finding 2:** `_checkLiquidationValid` logic flaw allows unfair liquidations or prevents valid ones.
* **Finding 3:** Interest logic in `borrowWithInterest` understates cross-chain debt, risking insolvency.
* **Finding 4:** CoreRouter prone to fund depletion due to miscalculated redemption payouts.
* **Finding 5:** Liquidators may under-liquidate positions due to `maxClose` using incomplete accrued balances.

#### Burve Protocol (Apr '25)
* **Finding 1:** Zero Tax Exploitation mechanism found in Withdrawal Function.
* **Finding 2:** Internal vs External vault share mismatch potentially traps user funds.
* **Finding 3:** **Critical:** ERC4626 inflation attack vector identified on underlying vault.

#### Yieldoor (Feb '25)
* **Finding 1:** Uninitialized `feeRecipient` diverts protocol fees to zero address (revenue loss).
* **Finding 2:** Calculation error impacts leveraged position holders.

</details>

---

### 🎓 Educational & Open Source
* **Damn Vulnerable DeFi Solutions:** My personal write-ups and solutions for the DVD wargame. [View Repository](https://github.com/M3dython/DAMN-DEFI)

---
<p align="center">
  <em>© 2025 M3dython. Open for audits and collaboration.</em>
</p>
