## Expected Domain and Message Hashes

First, we need to validate the domain and message hashes. These values should match both the values on your ledger and
the values printed to the terminal when you run the task.

> [!CAUTION]
>
> Before signing, ensure the below hashes match what is on your ledger.
>
> ### Nested Safe 1 (L1ProxyAdminOwner): `0xf66d0913Ee7f8518841Ae913853301Dd29b82298` - This safe is not nested.
>
> - Domain Hash: `0x3fe636801465d1c181289f70f03d57edc6aa3fa94e8dd619705c296e2f7ad372`
> - Message Hash: `0xdd54e9bd6b4fd6a6dc45c94e5a01e8e5343fd7e3a0e98f243939ae61bf32fd59` 


0x1901
3fe636801465d1c181289f70f03d57edc6aa3fa94e8dd619705c296e2f7ad372
0xdd54e9bd6b4fd6a6dc45c94e5a01e8e5343fd7e3a0e98f243939ae61bf32fd59


## Normalized State Diff Hash Attestation

The normalized state diff hash MUST match the hash created by the state changes attested to in the state diff audit report.
As a signer, you are responsible for making sure this hash is correct. Please compare the hash below with the hash in the audit report.

**Normalized hash:** `0xab23635c600a578e08ed092d78b3e877d2b361c76ff3b2e3522e8da46d1057ea`