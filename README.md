# ArgoCD App

This repo is for creation of argocd app. You can use argocd-apps/guestbook-staging-app.yaml to create the app or manually create on the UI by using this repo.

## Option 1

1. Push all of the above files to your Git repo.

2. Access the ArgoCD UI (on the Fleet Hub cluster).

3. Click "New App" > "From Git Repo".

4. Paste the repo URL and point to the path argocd-apps/guestbook-staging-app.yaml.

5. ArgoCD will pick it up and sync it to your Fleet Spoke Staging cluster.

## Option 2

1. Add this github path into it.
2. For the path, use apps/guestbook
   '
