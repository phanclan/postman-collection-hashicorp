## Import HashiCorp Vault Collection

1. Launch Postman
2. Click **Import**.
3. Click **Link**.
4. Enter the following URL:
https://raw.githubusercontent.com/phanclan/postman-collection-hashi-vault/master/Vault.postman_collection.json
5. Click **Continue**.
6. Confirm your import. Click **Import**.

## Environment Variables in Postman
You need to set the **Environments Variables**, from top-right corner, according to the requirement.

1. Click on **Manage Environment** from **Settings** (gear icon available at top right corner).
2. Click on **Add** button.
3. Specify the **Name** of the Environment. ex `Shipyard`
4. Fill **key** and **value**, which can be used as variables in collections later.
	* Variable: `VAULT_ADDR`
	* Value: `http://127.0.0.1`
	* Variable: `VAULT_TOKEN`
	* Value: `root`
5. Click **Add**