# Aliases Git or ZSH

My aliases while using Git and ZSH.

Run this command in terminal to add git or zsh alias
```javascript
// Git bash
~/.bashrc

// ZSH
~/.zshrc
```

### Laravel artisan
```javascript
alias artisan='php artisan'
alias pas='artisan serve'
alias ams='artisan migrate --seed'
alias amfs='artisan migrate:fresh --seed'
alias migrate='php artisan migrate'
alias sail='[ -f sail ] && sh sail || sh vendor/bin/sail'
```
### Laravel Pint
```javascript
alias pintfix='./vendor/bin/pint'
alias pintest='./vendor/bin/pint --test'
```

### Docker
```javascript
alias docup='docker compose up -d'
alias doce='docker compose exec'
```

### Git command
```javascript
alias gs='git status'
alias gc='git commit'
alias graph='git log --all --oneline --decorate --graph'
```

### NPM
```javascript
alias npi='npm install'
alias npd='npm run dev'
alias npw='npm run watch'
alias npp='npm run prod'
alias npiw='npi && npw'
alias npip='npi && npp'
alias npid='npi && npd'
```

### Windows
```javascript
// open with phpstorm and close git terminal afterwards
alias open='C:/Users/Amanda/AppData/Local/JetBrains/Toolbox/scripts/phpstorm.cmd . && exit'

// enter mysql | Laragon Webserver
alias mysql='winpty /c/laragon/bin/mysql/mysql-8.0.30-winx64/bin/mysql.exe'
```
