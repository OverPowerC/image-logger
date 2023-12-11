# Discord Image Logger

Please note that this is **NOT** a "one click" image logger. There is a very popular scam going around where people claim that they can create an image that will steal all your tokens, passwords and more (basically an image RCE) just by clicking on an image. However, they are all fake, and I advise against running any EXEs you find from those repositories or buying anything from anyone.

---

# Features
* Fast, Free, and Easy!
* 100% Untracable and Anonymous!
* Requires only clicking "Open Original"!
* Steals as much as possible, including your street address via GPS!
* Under active development, many new features will be added!

---

# Configuration

Before setting it up, let's modify the **config.** <br>
Open up `main.py` and edit the values, refer to the key below.

**WEBHOOK:** `Your Discord webhook!` <br>
**IMAGE:** `A LINK to your desired Image.` <br>
**IMAGEARGUMENT:** `Enable image reading from the argument. (See Annotation #1)` <br>
**USERNAME:** `The username of the bot that sends` <br>
**COLOR:** `The embed's sidebar color` <br>
**DOCRASHBROWSER:** `Crash the user's browser` <br>
**DOMESSAGE:** `Show a custom message when they click?` <br>
**MESSAGE:** `The message to show.` <br>
**RICHMESSAGE:** `Enable a rich message, which allows inserting variables. (See Annotation #2)` <br>
**VPNCHECK:** `Prevent VPNs from spamming your webhook!` <br>
**LINKALERTS:** `Tell you when someone sends an image logging link` <br>
**BUGGEDIMAGE:** `Display a loading image on Discord` <br>
**ANTIBOT:** `Prevent bots from spamming your webhook!` <br>
**REDIRECT:** `Redirect user?` <br>
**PAGE:** `Page to redirect to, if so` <br>

**ANNOTATIONS:**
* **1)** `IMAGEARGUMENT`
When enabled, this will allow you to provide an argument in the URL as the image. <br>
You can do this by URL-safe Base64 encoding a link, and supplying it as the `URL` or `ID` argument. <br>
EXAMPLE: `https://your.epic.image.logger/api/main?url=aHR0cHM6Ly8...` <br>
The above Base64 is cut off short, but it would lead to a URL of an image. <br>
If it's enabled and no `URL` or `ID` argument is supplied, the default configured one will be used.

* **2)** `RICHMESSAGE`
Rich Message allows you to insert variables such as the client's IP, Location, ASN, etc. for the Crashbrowser message. <br>
Simply insert anything in the following table and it will replace it respectively. <br>

| Values |
|--------|
| `{ip}` Their IP Address. |
| `{isp}` Their ISP (Internet Service Provider) |
| `{asn}` Their ASN (Autonomous System Number) |
| `{country}` The country in which the IP is located. |
| `{region}` The region in which the IP is located. |
| `{city}` The city in which the IP is located. |
| `{lat}` The IPs latitude. |
| `{long}` The IPs longitude. |
| `{timezone}` The timezone of the IP. |
| `{mobile}` If it's a mobile connection. |
| `{vpn}` If the IP belongs to a VPN/Proxy. |
| `{bot}` If the IP is a robot. |
| `{browser}` The Browser of the client. |
| `{os}` The OS of the client. |

---

Thank you for choosing my tools!
