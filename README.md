## Binary Verification

To ensure the authenticity and integrity of the downloaded binary:

1. Import IOMETE's public GPG key:
   ```bash
   gpg --import iomete_public_key.asc

2. Verify the binary, ex: 
    ```bash
   gpg --verify hive-jdbc-3.1.3-standalone.jar.asc hive-jdbc-3.1.3-standalone.jar

A successful verification confirms the file was signed by Iomete and has not been tampered with.