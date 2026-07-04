 # SecretVipEvents — Static Site

 This repository contains the static frontend for SecretVipEvents.

 Goal: deploy to GitHub Pages so others can access the site at a public URL.

 Quick setup & deploy (local -> GitHub):

 1. Initialize a local git repository (if not already):

 ```bash
 cd "c:\Users\schue\OneDrive\Desktop\Secretvipevents2"
 git init
 git add .
 git commit -m "Initial site"
 ```

 2. Create a GitHub repository (on github.com) named e.g. `secretvipevents2` and follow the instructions to add a remote, for example:

 ```bash
 git remote add origin git@github.com:<your-username>/secretvipevents2.git
 git branch -M main
 git push -u origin main
 ```

 3. The included GitHub Actions workflow will automatically deploy the repository to GitHub Pages on push to `main`.

 4. Visit `https://<your-username>.github.io/secretvipevents2/` after the workflow runs (may take a minute).

 Notes:
 - The workflow uses the official Pages actions. No extra tokens are required.
 - If you prefer Netlify or Vercel, I can provide deployment files for those services instead.

 If you want, I can run the `git` commands locally for you and/or create the remote repository, but you'll need to provide GitHub access (or do the `git push` step yourself).
