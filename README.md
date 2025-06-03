# Task 6: Password Strength Testing

#### By: Yug Dabgar (aka MASTERxD)

## Overview
For this task, I tested multiple passwords of different lengths and patterns using an online password strength checker. The goal was to understand what makes a password weak or strong and how attackers typically try to crack them.

## Tool Used
- [passwordmonster.com](https://www.passwordmonster.com)

## Passwords Tested

| Password         | Crack Time   | Verdict     |
|------------------|--------------|-------------|
| MASTERxD         | Instant      | ❌ Too short  
| MASTERxD@2165    | 18 Days      | ✅ Solid     
| Yugdabgar@123    | 86 Centuries | ✅ Strong    

Screenshots for each result are included in the folder.

## Key Learnings
- Passwords with **uppercase + lowercase + numbers + special symbols** are much stronger.
- **Length matters a lot** — longer passwords drastically increase crack time.
- Replacing common words with a **passphrase** or adding symbols helps defeat dictionary attacks.
- Strong passwords should avoid names, birth years, or simple patterns.

## Password Attacks to Know
- **Brute Force:** tries all combinations
- **Dictionary Attack:** uses a list of common passwords
- **Credential Stuffing:** reuses leaked credentials across sites

## Tip
Use a **password manager** to store complex passwords instead of reusing weak ones.

## Files
- `passwords_tested.txt` – Full results
- `screenshots/` – Password test screenshots
