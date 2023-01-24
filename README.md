<h1 align="center">
  <a href="https://github.com/loseys/Oblivion//"><img src="https://i.imgur.com/j1GdgLv.png" width="800" title="Oblivion"></a>
</h1>

[![platforms](https://img.shields.io/badge/platform-windows%20%7C%20linux-blue)](https://github.com/loseys/Oblivion/)
[![version](https://img.shields.io/badge/version-v1.0.0-blue)](https://github.com/loseys/Oblivion/)
[![Python 3.8.6](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-386/)
[![license](https://img.shields.io/badge/license-BSD-blue)](https://github.com/loseys/Oblivion/)

**Oblivion** is a tool focused in real time monitoring of new data leaks, notifying if the credentials of the user has been leak out. It's possible too verify if any credential of user has been leak out before. The Oblivion have two modes: 

- Oblivion Client: graphical mode.
- Oblivion Server: mode with API functionalities.

**NOTE**: The Oblivion Client and the Oblivion Server are independents.


<h1 align="center">
  <p style="text-align:center;">Oblivion Client</p>
  <a href="https://i.imgur.com/9SuF29i.png"><img src="https://i.imgur.com/uR0yHXj.png" width="800" title="Oblivion"></a>
  <p style="text-align:center;">Oblivion Server</p>
  <a href="https://i.imgur.com/uR0yHXj.png"><img src="https://i.imgur.com/9SuF29i.png" width="800" title="Oblivion"></a>
</h1>


### :cyclone: Oblivion Features

* 💪 CVEs scan
* ☑️ Works with powerful APIs
* 🔗 Works too with Google Dorks
* 🔎 Checks your password in Word Lists
* 👀 Checks the last pastes in Pastebin
* 📄 Output to txt, docx, pdf, xlsx, json, html, xml, db
* 🔒 Output to encrypted files
* 📦 Sends result files to multiples Buckets S3
* 📁 Upload the result files to Google Drive
* 📡 Cab send result files by SSH (work with EC2)
* 📢 Notify by Telegram and e-mail
* 📌 Includes option to hide passwords for demonstrations
* 🕒 Works with scheduled scans
* 🔁 Possible to execute loop scans
---

###  🔵 APIs

| Service | Functions | Status |
|-|-|-|
| [HaveIBeenPwned](https://haveibeenpwned.com/) | E-mails and passwords | paid |
| [Scylla.sh](https://scylla.sh/)| Cleartext passwords, hashs and salts, usernames, IPs, domain | free |
| [IntelX.io](https://intelx.io/signup)| Cleartext passwords, hashs and salts, usernames, IPs, domain, Bitcoin Wallets, IBAN | paid |
| [Circl.lu](https://cve.circl.lu/api/)| Checks for new CVEs| free |

-----

###  🔧 Usage and configuration

For configuration or usage of Oblivion please read the documentation. All the steps were careful explained with images and examples.


### ❗❗❗ IMPORTANT

1 - If you want only to use the free Oblivion (without the paid API keys) make sure that the free APIs are working.
Some times the free API of the Scylla.sh can be in manutence, and the Oblivion will return an error when you try to call the Scylla.sh API.

2 - Make sure that you are using the indicated OS and Python version. Some OS can be not compatible or return some types of error when you 
try to use Oblivion, for more information about compatibilities please read the Oblivion documentation.


###  💙 Thanks and credits

- Peter Kleissner and the Intelligence X team
- Alejandro Caceres (Scylla)
- <p><a href="https://github.com/khast3x/h8mail">khast3x</a></p>

- <p><a href="https://github.com/danielmiessler">Daniel Miessler</a></p>

- Gustavo Melgaço
- <p><a href="https://github.com/decastroalberico">Alberico de Castro</a></p>
- Eliabe Kaique
