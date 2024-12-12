
# Github Finder

## Environment Variables

To run this project, you will need to create and add the following environment variables to your .env file

`VITE_GITHUB_URL="https://api.github.com"`
`VITE_GITHUB_TOKEN="ghp_your-token"`

## Get Github Token

Create a GitHub account or log in to your existing account. Go to Settings, and in the left sidebar, find Developer settings. Click on it, and then in the left sidebar again, select Personal Access Tokens. Under that, go to Tokens (classic).

Click on Generate new token to create a token. The generated token will look something like this: `ghp_your-token`

## Run Locally

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd github-finder
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run dev
```
