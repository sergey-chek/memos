```bash
# Add files/directories to a specific archive:
zip -r path/to/compressed.zip path/to/file_or_directory1 path/to/file_or_directory2 ...

# Remove files/directories from a specific archive:
zip --delete path/to/compressed.zip path/to/file_or_directory1 path/to/file_or_directory2 ...

# Create an encrypted archive with a specific password:
zip -r --encrypt path/to/compressed.zip path/to/file_or_directory1 path/to/file_or_directory2 ...

# Archive files/directories to a multi-part [s]plit Zip archive (e.g. 3 GB parts):
zip -r -s 3g path/to/compressed.zip path/to/file_or_directory1 path/to/file_or_directory2 ...

# Print a specific archive contents:
zip -sf path/to/compressed.zip
```