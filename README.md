#GIT
alias stts='git status'
alias push='git push'
alias pull='git pull'
alias add='git add --all'
alias gcd='git checkout develop'
alias gcm='git checkout main'
alias checkout='git checkout .'
alias checkout-to='checkout-to() { git checkout "$1" ;};checkout-to'
alias commit='_commit() { git commit -a -m "$1" ;};_commit'
alias chore='_commit() { git commit -a -m "chore: $1" ;};_commit'
alias refactor='_commit() { git commit -a -m "refactor: $1" ;};_commit'
alias feat='_commit() { git commit -a -m "feat: $1" ;};_commit'
alias fix='_commit() { git commit -a -m "fix: $1" ;};_commit'
alias build='_commit() { git commit -a -m "build: $1" ;};_commit'
alias infra='_commit() { git commit -a -m "infra: $1" ;};_commit'

#TERMINAL
alias reload='exec bash' 

#EXE
alias start='npm start'