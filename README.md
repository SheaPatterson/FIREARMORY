# FireArmory Vault documentation

This repository contains the public Mintlify documentation for FireArmory Vault. The content is organized by task so readers can move from account setup to collection management, schematics, the caliber wiki, and security guidance.

The site configuration lives in `docs.json`, and each page is an `.mdx` file listed in the navigation.

## Local development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally:

```bash
npm i -g mint
```

Run the following command from this repository root, where `docs.json` is located:

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing

Connect this repository to your Mintlify project from the [Mintlify dashboard](https://dashboard.mintlify.com/settings/organization/github-app). Changes are deployed after they are pushed to the configured default branch.

## Need help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json` and that the page path is listed in `docs.json`.

### Resources

- [Mintlify documentation](https://mintlify.com/docs)
