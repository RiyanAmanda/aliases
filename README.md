# Aliases Git or ZSH

My aliases while using Git and ZSH.

Run this command in terminal to add git or zsh alias
```bash
# Git bash
nano ~/.bashrc

# ZSH
nano ~/.zshrc
```

### Laravel artisan
```bash
alias artisan='php artisan'
alias pas='artisan serve'
alias ams='artisan migrate --seed'
alias amfs='artisan migrate:fresh --seed'
alias migrate='php artisan migrate'
alias sail='[ -f sail ] && sh sail || sh vendor/bin/sail'
```
### Laravel Pint
```bash
alias pintfix='./vendor/bin/pint'
alias pintest='./vendor/bin/pint --test'
alias pretty='npx prettier . --write'
```

### Docker
```bash
alias docup='docker compose up -d'
alias docxe='docker compose exec'
```

### Git command
```bash
alias gs='git status'
alias gc='git commit'
alias gsw='git switch'
alias graph='git log --all --oneline --decorate --graph'
```

### NPM
```bash
alias rundev='pnpm run dev'
alias runwatch='pnpm run watch'
alias runprod='pnpm run prod'
alias runbuild='pnpm run build'
```

### Windows
```bash
alias openvs='code . && exit'
```
