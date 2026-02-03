Nice work, just some small issues. Please check them and correct them. 
Vault
- anchor-vault-starter-q4-25/programs/anchor-vault-q4-25/src/lib.rs:150: Close uses user without #[account(mut)], so the transfer/close cannot write to the recipient.
