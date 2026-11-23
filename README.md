# ORIGIN phone updates

Signed system images for the phone edition of ORIGIN (OnePlus 6).

- `origin/phone/update.txt`: build number, size, SHA-256 and ECDSA P-256 signature of the image
- `origin/phone/image`: the kernel image the description refers to

The phone checks the signature with the public key built into its kernel and refuses anything else.
Nothing here is secret: no keys, no personal data.
