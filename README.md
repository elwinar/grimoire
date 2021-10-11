# elwinar.com ansible box

## Requirements

- ansible
- community.general collection

## Using the vault

Using the `./vault.yml` file is required for accessing passwords & other
secrets. Add `-e @vault.yml` to the command-line to load the file, and give the
encryption secret when prompted.
