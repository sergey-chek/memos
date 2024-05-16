```bash
# Install gpg
sudo dnf install gpg

# Generate GPG-key
gpg --full-gen-key
gpg -k  # print public key info
gpg -K  # print private key info

# Encrypt/decrypt file with GPG-key
gpg -e -a -r <gpg-id> <path/to/file>  # encrypt as ASCII
gpg -d -o <output-filename> <path/to/encrypted-file>  # decrypt

# Export/import of GPG-keys
gpg --export -a <gpg-id> > public.gpg
gpg --export-secret-keys -a <gpg-id> > secret.gpg
gpg --import <path/to/public/gpg-key>
gpg --import <path/to/secret/gpg-key>

# Delete GPG-keys
gpg --delete-secret-keys <gpg-id>
gpg --delete-keys <gpg-id>
```
