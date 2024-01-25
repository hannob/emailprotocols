E-Mail protocols and data formats
=================================

Main protocols
--------------

* SMTP
* IMAP
* POP3

Mail structure and content
--------------------------

* MIME
* Mailheaders
* Header encoding (quoted-printable and base64)
* HTML
* uuencode (pre-MIME style)

MIME Content-Transfer-Encoding formats
--------------------------------------

* Common: 7BIT, 8BIT, BASE64, QUOTED-PRINTABLE
* Old/nonstandard: yencode, xxencode, uuencode

Additional TCP protocols and protocol variations
------------------------------------------------

* Sieve
* JMAP [RFC 8620](https://datatracker.ietf.org/doc/html/rfc8620)
* LMTP [RFC 2033](https://datatracker.ietf.org/doc/html/rfc8551)

Security Addons
---------------

* TLS
* STARTTLS
* SPF [RFC 7208](https://datatracker.ietf.org/doc/html/rfc4406) (+ obsolete SPF DNS record type)
* Sender ID (obsolete SPF alternative) [RFC 4406](https://datatracker.ietf.org/doc/html/rfc4406)
* DKIM [RFC 6376](https://datatracker.ietf.org/doc/html/rfc6376)
* DMARC [RFC 7489](https://datatracker.ietf.org/doc/html/rfc7489)
* Authenticated Received Chain (ARC) [RFC 8617](https://datatracker.ietf.org/doc/html/rfc8617)
* MTA-STS [RFC 8461](https://www.rfc-editor.org/rfc/rfc8461.html)
* DANE

Reporting
---------

* Delivery Status Notifications
* Message Disposition Notifications
* Abuse Reporting Format (ARF) [RFC 5965](https://datatracker.ietf.org/doc/html/rfc5965)
* DMARC reporting (XML)
* SMTP TLS reporting (JSON) [RFC 8460](https://datatracker.ietf.org/doc/html/rfc8460)

API
---

* sendmail commandline interface
* mail commandline interface

Login
-----

* SASL [RFC 4422](https://datatracker.ietf.org/doc/html/rfc4422)
* CRAM-MD5
* OAUTH/XOAUTH
* And many more: https://www.iana.org/assignments/sasl-mechanisms/sasl-mechanisms.xhtml

End-to-End encryption and signing
---------------------------------

* OpenPGP [RFC 4880](https://datatracker.ietf.org/doc/html/rfc4880) (including related protocols: Keyservers, WKD, ...)
* S/MIME [RFC 8551](https://datatracker.ietf.org/doc/html/rfc8551) (including related protocols: X.509, BIMI, ...)

Other
-----

* BURL [RFC 4468](https://www.rfc-editor.org/rfc/rfc4468.html)
* Autoresponder [RFC 3834](https://datatracker.ietf.org/doc/html/rfc3834)
* autoconfig
* DNS SRV records
* DNSBL [RFC 5782](https://datatracker.ietf.org/doc/html/rfc5782)
* Milter
* List-Unsubscribe-Post [RFC 8058](https://datatracker.ietf.org/doc/html/rfc8058)
