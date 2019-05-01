# bash-rsa
## RSA Encryption implemented using bash scripting
### Please don't use this for anything important



Files:
* genKeyPair - input: filename
  * This generates a new RSA key pair
* encrypt - input: public key, plaintext, outfile
  * Takes a public RSA key and plaintext to produce encrypted text
* decrypt - input: public key, ciphertext, outfile | output: plaintext
  * Takes a private RSA key and ciphertxt to restore the original text

