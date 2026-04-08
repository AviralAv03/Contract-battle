# 🏆 Galactic Leaderboard

*The bravest pilots in the galaxy are recorded here.*

<!-- LEADERBOARD_START -->
| Rank | Pilot | Highest Level | Timestamp (UTC) |
|------|-------|---------------|-----------------|
| 1 | Rohan-droid7341 | 4 | 2026-04-08 11:21:19 |
| 2 | chiragshirsath | 1 | 2026-04-08 11:31:44 |
<!-- LEADERBOARD_END -->

---

# Interstellar Vault 🚀

Welcome, spacefarer, to the Interstellar Vault! This is a competitive, level-based smart contract challenge designed to test your raw Solidity hacking and development skills across progressively devastating security flaws.

## How to Play

### 1. Setup the Template
To begin your journey, you must clone the mission repository:

1. **Fork this repository** to your own GitHub account.
2. **Clone your fork locally**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Contract-battle.git
   cd Contract-battle
   ```

### 2. Understand the File Structure
Your galactic workspace contains the following critical directories:
- `instructions/` — Contains your current mission briefing (e.g., `Level1.md`). Read this first to understand the vulnerabilities.
- `src/` — Contains the buggy smart contract template. **This is where you will write your code!**
- `test/` — Contains a lightweight local test file.
- `submit.sh` — The secure transmission script to submit your code to the Central Judge.

### 3. Install Foundry (The Environment)
This project uses pure native Solidity. You will need **Foundry** to run and compile your code.

**To install Foundry:**
* **Linux & macOS**: 
  ```bash
  curl -L https://foundry.paradigm.xyz | bash
  # Restart your terminal or run: source ~/.bashrc
  foundryup
  ```
* **Windows (Git Bash or WSL)**:
  ```bash
  curl -L https://foundry.paradigm.xyz | bash
  # Restart your terminal or run: source ~/.bashrc
  foundryup
  ```

### 4. Local Testing
Once you have modified the code in `src/LevelX.sol` to secure the vulnerabilities, run the local tests to ensure your baseline logic is dynamically sound:
```bash
forge test
```

### 5. Submission & Progression
When you are ready to face the Judge, do not commit. Instead, simply run:
```bash
./submit.sh
```
*(Your Pilot Name will be automatically detected safely via your GitHub identity).*

**The Galactic Judge:** Your terminal will securely transmit your code to the Central Judge. 
- A radar ping will appear in your terminal. The Judge is currently compiling and running **secret edge-case evaluator tests** against your smart contract.
- If you pass, your terminal will announce `ACCESS GRANTED` and the Judge will autonomously drop the next level's files straight onto your hard drive! 
- Your name will also be permanently etched into the Galactic Leaderboard above.
- There are **4 Levels** in total. If you conquer them all, you will receive the final broadcast!
- If you fail, access is denied. Examine your code locally and try again!
