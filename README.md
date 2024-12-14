![Repository Image]([https://socialify.git.ci/TheRealGeoDash2019/RammerheadBundlePatch/image?](https://raw.githubusercontent.com/crownytrex/rammerheadsers/refs/heads/main/image-ezgif.com-webp-to-png-converter.png)description=1&font=KoHo&forks=1&issues=1&logo=https%3A%2F%2Fsettings.lhost.dev%2Fassets%2FBetterRHLogo.png&owner=1&pattern=Charlie%20Brown&pulls=1&stargazers=1&theme=Auto)
# Rammerhead Bundle Patch
Modification of the Default Bundle from the Rammerhead Browser and partially improving it (feature-wise).

# How to Deploy?
- First, make a fork of [this repository](https://github.com/TheRealGeoDash2019/RammerheadBundlePatch/fork).

- Second, configure these [repository action secrets](../../settings/secrets/actions):
  - `CLOUDFLARE_ACCOUNT_ID` (Your Cloudflare Account ID: [Tutorial to find here](https://developers.cloudflare.com/fundamentals/setup/find-account-and-zone-ids/#find-account-id-workers-and-pages))
  - `CLOUDFLARE_API_TOKEN` (Cloudflare API Token with Edit Access to Workers & Pages)
  	- Go to [https://dash.cloudflare.com/profile/api-tokens](https://dash.cloudflare.com/profile/api-tokens)
    - Use the `Edit Cloudflare Workers` template
    - Give it Access to:
      - Account Resources: `All accounts`
      - Zone Resources: `Include` `All zones`
    - Click `Continue to summary` and click `Create Token`

- Finally, go to the [`Deploy to Workers`](../../actions/workflows/manual.yml) action and manually run the workflow!

# How to attach to sites?
- Read [wrangler.toml](./wrangler.toml) on how to setup routes.
