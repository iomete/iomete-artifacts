## Binary Verification

All current artifacts in this repository are signed with the **IOMETE Enterprise** GPG key (`iomete_enterprise_public_key.asc`).

To ensure the authenticity and integrity of a downloaded binary:

1. Import IOMETE's public GPG key:
   ```bash
   gpg --import iomete_enterprise_public_key.asc
   ```

2. Verify the binary, e.g.:
   ```bash
   gpg --verify hive-jdbc-3.1.3-standalone.jar.asc hive-jdbc-3.1.3-standalone.jar
   ```

A successful verification confirms the file was signed by IOMETE and has not been tampered with.

> **Legacy artifacts** under [`archive/`](./archive/) were signed with the older
> `iomete_public_key.asc` (kept in that folder). That key expires 2026-06-12;
> prefer the current artifacts above.
