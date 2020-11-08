
# Initialize the local directory as a Git repository.
git init

## Add files
git add .

## Commit your changes
git commit -m "First commit"

## Add remote origin
git remote add origin <Remote repository URL>
## <Remote repository URL> looks like: https://github.com/user/repo.git

## Verifies the new remote URL
git remote -v

## Push your changes
git push origin main

## Force (If previous is rejected)
git push origin main --force

# Clone an existing repository
git clone
