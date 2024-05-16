```bash
# Install and init
$ sudo dnf install pass
$ pass init <gpg-id>  # creates ~/.password-store/
$ pass init -p <gpg-id1> -p <gpg-id2>  # use multiple keys

# Add password
$ pass insert Email/example@gmail.com
$ pass insert Email/example@gmail.com -m  # multiline
$ pass generate Email/example@gmail.com 15  # generate a 15-char pass 

# Show password
$ pass  # list all passwords
$ pass Email/example@gmail.com  # print pass
$ pass -c Email/example@gmail.com  # copy pass to clipboard

# Remove pass
pass rm Email/example@gmail.com

# Use password-store as a git repo
# If a git repo is initialised, pass creates a git commit each time when the store is changed
$ pass git init
$ pass git remote add origin <origin>
```