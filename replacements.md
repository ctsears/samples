1. Changed

2.  Next add the secret to the Vault with this command. Be sure to change the placeholder text to your vault name.

    ```powershell
    $secret = Set-AZKeyVaultSecret -VaultName 'YourVaultName' -Name&nbsp;'SQLPassword' -SecretValue $secretvalue
    ```
