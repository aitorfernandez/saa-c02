## Key management service

- Regional secure key management and encryption and decryption.

- Manages customer master keys (CMKs) a logical representation of a key, a pointer or reference to some underlying cryptographic material.

- Them CMKs never leave the region.

- Ideal for S3 objects, database passwords and API keys stored in Systems Manager Parameter Store.

- Encrypt and decrypt data up to 4KB in size.

- Integrated with most AWS services.

- Pay per API call, listing, encrypt, decrypt, reencrypt

- KMS supports audit capability using CloudTrail.

- KMS is FIPS 140-2 Level 2

- Level 3 is CLoudHSM has even more stringent security mechanisms.

- Types

  - AWS Managed CMK, Free, used by default if you pick encryption in most AWS services.
  - Customer Managed CMK, allows key rotation controlled via key policies and can be enabled/disabled.
  - AWS Owned CMK, used by AWS on a shared basis across many accounts.

- Symmetric

  - Same key for encryption and decryption.
  - AES-256

- Asymmetric

  - Mathematically related to public/private key pair.
  - RSA and elliptic-curve cryptography (ECC).
  - Private key never leaves AWS.
  - Must call the KMS APIs to use private key.
  - Download the public key and use outside AWS.
  - AWS services integrated with KMS do not support asymmetric CMKs.
