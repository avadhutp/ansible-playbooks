## Testing
Test if a host is reachable via ansible (when running remotely) using the following command:
`ansible crab -i hosts -m ping --ask-vault-pass`

## Run a playbook 
1. To run: `sudo ansible-playbook -i hosts site.yml --ask-vault-pass`
1. This will ask for the vault password, which is used to decrypt the file that stores all the passwords: MySQL, System, etc.