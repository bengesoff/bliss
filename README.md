![Bliss](./logo/logo.png)

[![Build Status](https://travis-ci.org/ajmwagar/bliss.svg?branch=master)](https://travis-ci.org/ajmwagar/bliss)
[![dependency status](https://deps.rs/repo/github/ajmwagar/bliss/status.svg)](https://deps.rs/repo/github/ajmwagar/bliss)


> **Ignorance is bliss!** Ignore your `.gitignore`.

*Bliss* is a "batteries included" `.gitignore` management tool.

## Features

- Pulls `.gitignore`s from [gitignore.io](https://gitignore.io).
- Built-in caching allows for **offline use** and **blazing fast** speeds. (After inital download of `.gitignore` templates)
- Simple, stateless CLI
- Zero system-dependencies (standalone binary) 
<!-- - Multi-threading and Parallelism via [`rayon`](https://github.com/rayon-rs/rayon)-->

## ⚒ Usage

```bash

bliss list # Print out supported languages

bliss rust # print out a rust .gitignore

bliss rust,python # print out a rust and python .gitignore

bliss rust >> .gitignore # Append rust's .gitignore to ./.gitignore

bliss help # Show help menu

bliss help cache # Shows help for cache command
```


## 📦 Installation

```bash
cargo install bliss
```
## 🚥 Roadmap

- [x] `.gitignore` Caching
- [x] Better cache management
- [x] Better error handling/messages
- [ ] More commands for handling common issues and mistakes with `.gitignore` files.
- [ ] MOAR SPEED!!!!
- [ ] The heat-death of the universe...
