# For testnet network please follow steps.

```
- Enter the running container
- Edit mcedit /usr/local/bin/alias_oneshot
- Add option exec aliaswalletd ```"${args[@]}" -testnet the last line


# Example how to use json prc to send amoutn from node to address
walletpassphrase <passphrase> <timeout> 