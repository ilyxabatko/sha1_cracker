# A simple SHA-1 Cracker implementation in Rust
The program tries to crack a provided SHA-1 digest of a password by hashing the passwords from the wordlist.txt (a set of commonlty used passwords) and asserting both hashes. 

I wrote the implementation following the explanation from the "Black Hat Rust" book.

## Run:
```
cargo run -- wordlist.txt 7c6a61c68ef8b9b6b061b28c348bc1ed7921cb53
```