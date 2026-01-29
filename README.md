# SHA256 Password Cracking Practice (hashcat)

This repository contains a **hands-on practice lab** for cracking **SHA256** password hashes using **hashcat** with the **RockYou wordlist** and rules.

**Ethical Use Warning**  
These techniques are used **only for educational purposes**, such as:
- Personal learning labs
- CTF challenges
- Authorized test environments  

Never attack real systems or hashes without proper permission.

---

## Usage

```bash
git clone https://github.com/md-samrat/sha256_hashes-cracking-by-hashcat.git
cd sha256_hashes-cracking-by-hashcat
hashcat -m 1400 -a 0 sha256.txt /usr/share/wordlists/rockyou.txt
hashcat -m 1400 sha256.txt --show 
