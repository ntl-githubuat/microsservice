# Create repo using API!

curl -L \
  -X POST \
  -H "Accept: application/vnd.github+json" \
  -H "Authorization: Bearer <YOUR-TOKEN>" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  https://api.github.com/orgs/ORG/repos \
  -d '{"name":"Hello-World","description":"This is your first repository API-LAB","homepage":"https://github.com","private":false,"has_issues":true,"has_projects":true,"has_wiki":true}'

  # Update token
  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 # 30days Key expire

  curl -L \
  -X POST \
  -H "Accept: application/vnd.github+json" \
  -H "Authorization: Bearer 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" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  https://api.github.com/user/repos \
  -d '{"name":"Hello-World","description":"This is my test repo_v1!","homepage":"https://github.com","private":false,"is_template":true}'

  # Step-2
  git clone git@github.com:ntl-githubuat/Hello-World.git

  # Step-3 Create 3 files 

  # Step-4 
  git status


  # Step-5
   git mv blue-deploy.yaml blue-statefulset.yaml
   git add -u # update
   git status
   git add -A #
   git commit -m "Changed blue-statefulset.yaml"

   git log --oneline --graph --decorate --all

   git checkout -b feature
   git diff main features
   