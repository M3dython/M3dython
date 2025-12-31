<h1 align="center">Hi there, I'm M3dython 👋</h1>

<h3 align="center">
  Blockchain Security Researcher | Smart Contract Auditor | Full Stack Developer
</h3>

<p align="center">
  <a href="https://m3dython.com"><strong>🌐 m3dython.com</strong></a>
</p>

<p align="center">
  <em>Identifying and mitigating vulnerabilities in decentralized protocols before they hit mainnet.</em>
</p>

---

### 👨‍💻 About Me

I’m **M3dython**, a specialized Blockchain Security Researcher focused on DeFi protocol architecture. I actively compete in top-tier audit contests like **Sherlock**, where I’ve earned recognition for identifying High/Critical vulnerabilities in complex financial logic.

My mission is to help projects scale securely. I bridge the gap between raw code and business logic to prevent treasury-draining exploits.

* 🔭 **Focus:** Advanced smart contract security patterns & auditing.
* 🌱 **Learning:** Solidity Fuzzing (Foundry/Echidna) and Formal Verification.
* 🛡️ **Services:** Available for private audits and consultation.
* ⚡ **Fun fact:** I find uncovering subtle logical flaws in Web3 protocols incredibly rewarding.

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

| Contest | High | Medium | Report | Rank |
| :--- | :---: | :---: | :---: | :---: |
| **[LEND (May '25)](https://audits.sherlock.xyz/contests/908)** | 4 | 1 | [Read Report](https://github.com/sherlock-audit/2025-05-lend-audit-contest-judging/issues) | **52nd** |
| **[Burve (Apr '25)](https://audits.sherlock.xyz/contests/858)** | 3 | - | [Read Report](https://github.com/sherlock-audit/2025-04-burve) | **8th** |
| **[PinLink RWA (Mar '25)](https://github.com/sherlock-audit/2025-03-pinlink-rwa-tokenized-depin-marketplace)** | - | - | [Read Report](https://github.com/sherlock-audit/2025-03-pinlink-rwa-tokenized-depin-marketplace-judging/blob/main/167.md) | **39th** |
| **[Yieldoor (Feb '25)](https://audits.sherlock.xyz/contests/791)** | 1 | 1 | [Read Report](https://github.com/sherlock-audit/2025-02-yieldoor) | **15th** |

<br>

### 🔍 Detailed Findings Breakdown

<details>
<summary><strong>📂 Click to expand specific vulnerability details</strong></summary>

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

#### PinLink DePIN (Mar '25)
* **Finding:** Centralized Oracle updates vulnerable to front-running, causing user payout loss.

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
