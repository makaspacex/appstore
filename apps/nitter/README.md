# Nitter

[![Test Matrix](https://github.com/zedeus/nitter/workflows/Tests/badge.svg)](https://github.com/zedeus/nitter/actions/workflows/run-tests.yml)
[![Test Matrix](https://github.com/zedeus/nitter/workflows/Docker/badge.svg)](https://github.com/zedeus/nitter/actions/workflows/build-docker.yml)
[![License](https://img.shields.io/github/license/zedeus/nitter?style=flat)](#license)

A free and open source alternative Twitter front-end focused on privacy and
performance. \
Inspired by the [Invidious](https://github.com/iv-org/invidious)
project.

- No JavaScript or ads
- All requests go through the backend, client never talks to Twitter
- Prevents Twitter from tracking your IP or JavaScript fingerprint
- Uses Twitter's unofficial API (no rate limits or developer account required)
- Lightweight (for [@nim_lang](https://nitter.net/nim_lang), 60KB vs 784KB from twitter.com)
- RSS feeds
- Themes
- Mobile support (responsive design)
- AGPLv3 licensed, no proprietary instances permitted