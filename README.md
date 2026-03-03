<!-- <img src=".github/assets/banner.png" alt="YAFA Banner" width="100%"> -->

<div align="center">
  <h1>YAFA (Yet Another Flashcard App)</h1>
  <p>A free, open-source, spaced-repetition flashcard application focused on digital preservation.</p>
</div>

<div align="center">
  <img src="https://www.google.com/search?q=https://img.shields.io/github/license/vcnbianchi/yafa%3Fstyle%3Dflat-square" alt="License" />
  <img src="https://www.google.com/search?q=https://img.shields.io/github/stars/vcnbianchi/yafa%3Fstyle%3Dflat-square" alt="Stars" />
</div>

# Proposal
To develop an open-source, free, self-hosted, multiplatform, and minimalist flashcard application featuring built-in spaced repetition functionality.

# The Problem
There are currently many flashcard applications available, ranging from free and "freemium" to paid models. However, few manage to be free, open-source, and focused on digital preservation. Much of the current ecosystem suffers from vendor lock-in, where user knowledge is trapped in proprietary formats or dependent on closed servers and subscription plans. This makes it difficult for users to maintain long-term control over their own data and study materials.

# The Solution
YAFA aims to solve this scenario based on the following pillars:
1. **Digital Preservation**: YAFA is a self-hosted application, ensuring that users maintain full sovereignty over their data;
2. **Universal Format**: Application data is not saved in proprietary files, but in open formats widely adopted by other tools and easily readable by humans;
3. **Free**: YAFA is built to be free for everyone, forever;
4. **Open Source**: The source code is available to everyone (check the license), forever.

## Project Structure
The repository is strictly divided between applications and packages.

```
yafa/
├── apps/               # Interface directory
│   ├── desktop/        # Desktop Interface
└── packages/           # Packages directory
    ├── api/            # Business logic
```
