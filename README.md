# Cryptographic-Attacks

## Cryptographic Attacks
**English:**
A cryptographic attack is when someone tries to break or weaken encryption, hashing, or other security mechanisms by exploiting weaknesses in the algorithms, keys, or their implementation.

**Urdu:**
Cryptographic attack ka matlab hota hai ke attacker encryption ya hashing system ko todne ki koshish kare, ya uski kamzori ka faida uthaye — chahe algorithm ka fault ho, key ka guess ho, ya system implementation ka flaw ho.

## Common Types of Cryptographic Attacks
### Downgrade Attack
**English:**
This attack forces a system to use an older, weaker version of an encryption protocol (like forcing HTTPS to use SSL 2.0 instead of TLS 1.3). Weaker versions have known vulnerabilities, so they’re easier to break.

**Urdu:**
Downgrade attack mein attacker system ko majboor karta hai ke woh purana aur kamzor encryption version use kare. Purane version me bugs hote hain jo attacker easily exploit kar sakta hai.

### Side Channel Attack
**English:**
Instead of breaking the encryption mathematically, the attacker studies physical leaks like power usage, timing, electromagnetic signals, or sound to deduce the key.
**Urdu:**
Side channel attack mein attacker encryption solve nahi karta, balki device ke signals, power ka use, time delay, ya noise observe karke key ka pata lagata hai.

### Cryptovariable / Key Attack
**English:**
A key attack focuses on guessing, stealing, or calculating the secret cryptographic key used for encryption/decryption. Without the key, encrypted data can’t be read, but once the key is found, everything is exposed.

**Urdu:**
Key attack ka matlab hai key ko guess karna, churana ya mathematically calculate karna. Jab key mil jaye toh pura encrypted data read ho sakta hai.

### Hash Attack
**English:**
These target hashing algorithms. The goal is to find two inputs that produce the same hash (collision) or reverse-engineer the original input from the hash (preimage attack).

 **Urdu:**
Hash attack mein attacker hashing function ko todne ki koshish karta hai — ya toh do alag data find kare jo same hash de (collision), ya hash se original data ka guess kare.

### Rainbow Table Attack
**English:**
A rainbow table is a large precomputed database of hash values for common passwords. Attackers use it to reverse hashes into original passwords quickly, instead of brute-forcing each time.

**Urdu:**
Rainbow table ek badi list hoti hai jisme pehle se passwords ke hashes store hote hain. Attacker is table ko use karke hash ka match find karke original password jaldi nikal leta hai.

## the summary table

### Attack ---------------------------------------------------------Type	Explanation

Downgrade Attack ---------------------------	Forces a system to use an older, weaker encryption version, making it easier to break.

Side Channel Attack-----------------------------	Exploits physical leaks (e.g., power usage, timing, electromagnetic signals) to deduce the encryption key.

Cryptovariable / Key Attack ----------------------	Focuses on guessing, stealing, or calculating the secret cryptographic key.

Hash Attack ----------------------------------------	Attempts to find collisions or reverse-engineer the original input from a hash value.

Rainbow Table Attack -----------------------------	Uses precomputed hash databases to quickly reverse hashes into original passwords.
