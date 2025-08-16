# Mezcal

## Overview
Mezcal is a Python-based spammer that sends bulk emails using pre-configured SMTP accounts.  
The script is written with a fun and whimsical style, but all execution and consequences are the responsibility of the user.

**Disclaimer:** This tool is provided "as-is". The developer assumes no responsibility for misuse, abuse, or any legal consequences resulting from the use of this tool. The user is fully responsible.

---

## Features
- Automatic login to multiple pre-configured email accounts.
- Send bulk emails to any target of your choice.
- Random headers for each email (X-Mailer, X-Priority, X-Originating-IP, etc.).
- Adjustable delay between emails.

---

## Requirements
Install the required Python packages listed in `requirements.txt`:

```bash
pip install -r requirements.txt
````

`requirements.txt` content:

```
colorama==1.4.6
tabulate==0.9.0
```

> Note: Standard Python packages such as `smtplib`, `ssl`, `random`, `time`, and `email` are included in Python and do not need to be installed separately.

---

## Usage

1. Clone the repository:

```bash
git clone https://github.com/KiddTheReaper/Mezcal.git
cd Mezcal
```

2. Run the script:

```bash
python mezcal.py
```

3. Choose an account from the table:

```
Choose account (1-7):
```

4. Enter the target email, subject, message body, number of emails, and delay between sends.

5. The script will send emails according to your settings.

---

## Example Accounts

The script comes with some ready-to-use accounts:

| No | Email                                                                                 |
| -- | ------------------------------------------------------------------------------------- |
| 1  | [sh1tb0mb@national.shitposting.agency](mailto:sh1tb0mb@national.shitposting.agency)   |
| 2  | [fucky0ub1tch@horsefucker.org](mailto:fucky0ub1tch@horsefucker.org)                   |
| 3  | [b1tchr1d3r@cocaine.ninja](mailto:b1tchr1d3r@cocaine.ninja)                           |
| 4  | [r1pp3r@aaathats3as.com](mailto:r1pp3r@aaathats3as.com)                               |
| 5  | [narcoticservice@420blaze.it](mailto:narcoticservice@420blaze.it)                     |
| 6  | [nati0nal.sh1tposting.ag3ncy@gmail.com](mailto:nati0nal.sh1tposting.ag3ncy@gmail.com) |
| 7  | [s3cr3t.1ns4n1ty.s3rv1ce@gmail.com](mailto:s3cr3t.1ns4n1ty.s3rv1ce@gmail.com)         |

---

## Disclaimer

Use this tool wisely and at your own risk.
