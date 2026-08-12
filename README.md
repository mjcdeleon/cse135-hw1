# cse135-hw1
# CSE 135 — HW1: Client Side Basics, Site and Server Configuration

## Team Members
- Justin Nguyen
- Macy De Leon

## Live Site
- Main: https://jmcse135-hw1.site
- Collector: https://collector.jmcse135-hw1.site
- Reporting: https://reporting.jmcse135-hw1.site

---

## Grader Login Information
- **Server IP:** 137.184.20.185
- **Grader username:** `grader`
- **Grader password:** `CSE135` or none

If root uses an SSH key, the grader account also uses one:
- **Private key for grader account:** `-----BEGIN OPENSSH PRIVATE KEY-----
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
-----END OPENSSH PRIVATE KEY-----`
- **Passphrase (if any):** `None`

---

## Site Login (Basic Auth)
- **Username:** `[FILL IN]`
- **Password:** `[FILL IN]`

---

## GitHub Auto-Deploy
- **Repo URL:** `(https://github.com/mjcdeleon/cse135-hw1.git)`
- **Method:** The server web root is a git clone of our repo. A cron job runs a deploy
  script every minute that fetches and hard-resets the web root to match the `main`
  branch, so any push to `main` goes live automatically within about a minute.

Setup:
1. Cloned the repo into the web root:
   ```
   cd /var/www/jmcse135-hw1.site
   sudo git init
   sudo git remote add origin https://github.com/[USER]/[REPO].git
   sudo git fetch origin
   sudo git checkout -f main
   ```
2. Created `/usr/local/bin/deploy.sh`:
   ```
   #!/bin/bash
   cd /var/www/jmcse135-hw1.site
   git fetch origin main
   git reset --hard origin/main
   ```
   `sudo chmod +x /usr/local/bin/deploy.sh`
3. Scheduled with `sudo crontab -e`:
   ```
   * * * * * /usr/local/bin/deploy.sh >> /var/log/deploy.log 2>&1
   ```

See `github-deploy.gif` for the deploy process.

---

## Compression Summary
`[FILL IN ]`

---

## Server Header Change
`[FILL IN]`
