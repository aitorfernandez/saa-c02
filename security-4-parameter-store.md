## System Manager Parameter store

- Serverless scalable and high performance system for storing data and secrets, things like passwords, database connections, API keys, etc.

- Values can ve encrypted (KMS) or plaintext.

- Store parameters in hierarchies up to 15 levels

  - dev -> db -> mysql
  - dev -> app -> apikey
  - prod -> db -> mysql
  - prod -> app -> apikey

- Track versions.

- Set TTL to expires values such as passwords.

- Parameter store comes with no additional charges.

- Limit currently is 10000.
