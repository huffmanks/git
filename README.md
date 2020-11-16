# Initialize a local directory as a Git repository.
git init

### Add files
git add .

### Commit your changes
git commit -m "First commit"

### To main branch
git branch -M main

### Add remote origin
git remote add origin https://github.com/user/repo.git

### Push your changes
git push -u origin main

### Force (If necessary)
git push origin main --force

# Clone an existing repository
git clone https://github.com/user/repo.git
