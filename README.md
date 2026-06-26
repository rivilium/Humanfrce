# Humanfrce

Shared platform repository for the Humanfrce project.

This repository is intended to be the common upstream for:

- publishing platform changes for colleagues to access
- pulling the latest shared work into local development environments
- keeping project setup and operating notes in one public place

## Working With The Repo

Clone the repository:

```powershell
git clone https://github.com/rivilium/Humanfrce.git
cd Humanfrce
```

Pull the latest changes before starting work:

```powershell
git pull origin main
```

Push local commits:

```powershell
git push origin main
```

## Public Repository Note

Do not commit secrets, access tokens, private customer data, internal credentials, or environment-specific configuration values. Use local `.env` files for private settings and document required variables without values.
