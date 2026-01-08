# P.0.R.N. (Project Onboarding Retail Normies)

---

![Python Version](https://img.shields.io/badge/python-3.9+-blue.svg)
![Status](https://img.shields.io/badge/status-alpha-yellow.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

**P.0.R.N. Project** is a tool designed to revolutionize memecoin adoption by targeting... *untapped demographics*.

This bot is a proof-of-concept for strategic, high-volume comment-based marketing, funneling new users to **memecoins on pump.fun**.

**Disclaimer:** This project is a proof-of-concept. Any use of this tool must comply with the Terms of Service of all targeted platforms. Use at your own risk!

---

### Features (Roadmap)
* [x] Core loop and logging
* [ ] Module for new content identification
* [ ] API connection and authentication module
* [ ] Anonymous posting action

### Installation

1.  Clone the repository:
    ```bash
    git clone [https://github.com/](https://github.com/)[reldeddevs]/P.0.R.N.-Project-Onboarding-Retail-Normies.git
    ```

2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

### Configuration
The bot is configured via environment variables. See `docs/CONFIG.md` for details.

1.  Create a `.env` file in the root directory.
2.  Add your API credentials and comment template.
    ```ini
    # .env
    # --- API Credentials ---
    PLATFORM_API_KEY="YOUR_SUPER_SECRET_KEY"
    PLATFORM_SECRET="NOT_TELLING_YOU_BRO"
    
    # --- Bot Configuration ---
    TARGET_TOPIC="trending"
    COOLDOWN_MIN_SECONDS=300
    
    # --- Comment Payload ---
    COMMENT_TEMPLATE="Sup you gooner. Want to make some serious money? Buy $P.0.R.N. its a memecoin on Pump.Fun, easy 1000x. Just go to Pump.Fun, type in P.0.R.N, invest, sit back and relax. Thanks gooners"
    ```
