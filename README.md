# Big Text Area

This app is just a gigantic text area for storing content

## Development

This application does not have any included tooling like Rollup, Vite, or even a Package Manifest (like `package.json`)

For convenience, a devcontainer configuration is offered at `/.devcontainer/devcontainer.json`

### Start a Dev Server

In order to review your changes locally, you will need to run a local development server using whatever tooling your development system supports.

If developing using the included devcontainer configuration, this could be Python's included HTTP server

```bash
# From the project root

python3 -m http.server 8080
```

### Run tests

This project has no included tests

## Deployment

### Deploying to Preview Environments

GitHub is configured to use the Netlify extension to deploy branches to a preview environment when a pull request to the `master` branch is opened

### Deploying to Production

Netlify is configured to deploy all changes merged to `github.com/ianjmacintosh/bigtextarea/tree/master` to production
