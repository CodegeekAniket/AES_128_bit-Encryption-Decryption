# 🔐 AES-128 Encryption & Decryption Engine (Verilog HDL)

A fully modular and synthesizable AES-128 encryption and decryption engine built in Verilog HDL, conforming to the [NIST FIPS-197] standard. This project is suitable for secure communication systems and embedded cryptographic hardware.

---

## 📌 Features

- ✅ Supports both AES-128 encryption and decryption
- 🔄 Implements all core AES transformations:
  - `SubBytes` / `InvSubBytes`
  - `ShiftRows` / `InvShiftRows`
  - `MixColumns` / `InvMixColumns`
  - `AddRoundKey`
  - `KeyExpansion` / inverse key schedule
- 📦 Modular RTL design for ease of reuse and extension
- 🧪 Verified with official NIST AES test vectors
- 🧩 Cleanly structured for synthesis and FPGA implementation

---

## 🚀 Use Cases

- 🔐 Secure data encryption in hardware accelerators
- 📡 FPGA-based cryptographic engines for embedded systems
- 📈 Baseline core for further pipelined or parallel AES enhancements

---

## 🛠️ Tools Used

| Tool       | Purpose                     |
|------------|-----------------------------|
| Verilog HDL | RTL design                 |
| Vivado      | Synthesis and timing analysis |

---



## 🧪 Simulation & Verification

- Simulated using **Vivado**
- Verified against known **NIST test vectors** for correctness
- Outputs compared for bit-accuracy across encryption and decryption cycles

---

## 🧠 Future Improvements

- Add pipelined AES core for higher throughput
- Implement AES-192 / AES-256 support
- Integrate Galois Counter Mode (GCM) for authenticated encryption
- Target real-time secure communication interface (e.g., SPI or UART with AES)

---

## 📚 References

- [FIPS-197: Advanced Encryption Standard (AES)](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.197.pdf)
- [NIST Cryptographic Algorithm Validation Program](https://csrc.nist.gov/projects/cryptographic-algorithm-validation-program)

---



