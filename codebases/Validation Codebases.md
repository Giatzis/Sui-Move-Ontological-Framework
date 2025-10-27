# 🔒 Validation Codebase URLs

These are the links for the codebases used for our external validation. The codebases as they existed until September 24, 2025, are located in the folder `Codebases (24 September 2025)`, and can be directly downloaded from this folder or visit the links below.<br><br>
You can copy each link into your browser or use tools like `curl` or `wget` to download the files directly.

---

## 1. Access Control Pattern

**File:** `transfer_policy.move`  
**Commit:** `c3de14d`  
**Description:** Access control implementation for kiosk transfer policies.

**Raw URL:**  
```text
https://raw.githubusercontent.com/MystenLabs/sui/c3de14d/crates/sui-framework/packages/sui-framework/sources/kiosk/transfer_policy.move
```

---

## 2. Circuit Breaker Pattern

**File:** `coin.move`  
**Commit:** `c3de14d`  
**Description:** Implements circuit-breaking logic within Sui’s coin module.

**Raw URL:**  
```text
https://raw.githubusercontent.com/MystenLabs/sui/c3de14d/crates/sui-framework/packages/sui-framework/sources/coin.move
```

---

## 3. Escapability Pattern

**File:** `package.move`  
**Commit:** `c3de14d`  
**Description:** Demonstrates the escapability pattern for Move packages.

**Raw URL:**  
```text
https://raw.githubusercontent.com/MystenLabs/sui/c3de14d/crates/sui-framework/packages/sui-framework/sources/package.move
```

---

## 4. Time Incentivization Pattern

**Example:** `linear.move` (from Sui Docs)  
**Description:** Illustrates linear vesting strategies and time-based tokenomics.

**Raw URL:**  
```text
https://docs.sui.io/concepts/tokenomics/vesting-strategies?raw=true
```

---

### 🧩 Notes

- All URLs point to **immutable** commit-specific versions for reproducible validation (except the Time Incentivization Pattern).
- Duplicate links were removed for clarity.
- You can use `curl` or `wget` for quick download, for example:
  ```bash
  curl -O https://raw.githubusercontent.com/MystenLabs/sui/c3de14d/crates/sui-framework/packages/sui-framework/sources/coin.move
  ```
