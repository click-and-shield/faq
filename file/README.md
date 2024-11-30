# FAQ

## What makes "Click & Shield File" a secure solution?

"Click & Shield File" employs state-of-the-art AES-256 encryption in CBC mode, fortified by a randomly generated initialization vector (IV). The encryption key is securely derived using PBKDF2WithHmacSHA256 with 65,536 iterations, and file integrity is meticulously ensured through an MD5 checksum.

Let's get straight to the point:

In June 2003, the U.S. Government announced that AES could be used to protect classified information (source: [Cryptographic Standards and Guidelines](https://csrc.nist.gov/projects/cryptographic-standards-and-guidelines/archived-crypto-projects/aes-development) - archive: [CNSS Policy No. 15, Fact Sheet No. 1](https://github.com/click-and-shield/assets/blob/master/pdf/aes-fact-sheet.pdf)):

> “The design and strength of all key lengths of the AES algorithm (i.e., 128, 192 and 256) are sufficient to protect classified information up to the SECRET level. TOP SECRET information will require use of either the 192 or 256 key lengths.“ 

* *Is "Click & Shield File" effective for protecting your files from hackers?* Absolutely — there’s no doubt, provided you use a strong secret key.
* *Is "Click & Shield File" effective for safeguarding your files from organized crime groups?* Absolutely — there’s no doubt, provided you use a strong secret key.
* *Is "Click & Shield File" suitable for protecting your files from private corporations?* Absolutely — there’s no doubt, provided you use a strong secret key.
* *Is "Click & Shield File" suitable for protecting your files from GAFAM?* Absolutely — there’s no doubt, provided you use a strong secret key.
* *Is "Click & Shield File" secure against public agencies?* For the majority of cases, yes, provided you use a strong secret key. However, if by "public agencies" you mean entities like the NSA, we would say "probably not."
