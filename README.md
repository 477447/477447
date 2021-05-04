- 👋 Hi, I’m @477447
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

GitHub CLI
gh is GitHub on the command line.It brings pull reguests, issues, and other GitHub concepts to the terminal next to where you are
already working with git and your code.


Installation

You can find installation instructions on our README.
gh

                   

GitHub CLI
gh is GitHub on the command line. It brings pull requests, issues, and other GitHub concepts to the terminal next to where you are already working with git and your code.

Installation
You can find installation instructions on our README.

Authentication
Run gh auth login to authenticate with your GitHub account. gh will respect tokens set using GITHUB_TOKEN.

GitHub Enterprise Server
GitHub CLI supports GHES 2.20 and above. To authenticate with a GitHub Enterprise instance, run:

gh auth login --hostname <hostname>
You will be prompted to either authenticate using your browser, or to paste a token.
  
  GitHub GLI
  
  gh is GitHub on the command line. It brings pull reguests, issues, and other GitHub concepts to the terminal next to where you are already
  
  Installation
  You can find instalallation instructions on our README.
  
  Authentication
  Run gh auth login to authenticate with your GitHub account. gh will respect tokens set using GITHUB_TOKEN.
  
  GitHub Enterprise Server
  
  GitHub CLI supports GHES 2.20 and above.To authenticate with a GitHub Enterprise instance, run:
  
    gh auth login --hostname <hostname>
    You will be prompted to either authenticate using your browser, or to paste a token.
    

gh config get
Print the value of a given configuration key

 gh config get <key> [flags]
  
  Examples
  
    $ gh config get git_protocol
    https
    
    Options
         -h, --host string Get per-host setting
         
         Options inherited from parent commands
         
                 --help  Show help for command
           
           
 
                     $ gh pr checks
                 View your pull reguests'checks.
                 
     $ gh pr checks
     All checks were successful
     1 failing, 3 successful,and 1 pending checks
     
     - CodeQL                    3m43s     https://github.com/cli/cli/runs/123
       build (macos-latest)       4m18s     https://github.com/cli/cli/runs/123
       build (ubuntu-latest)      1m23s     https://github.com/cli/cli/runs/123
       build (windows-latest)     4m43s     https://github.com/cli/cli/runs/123
       lint                       47s       https://github.com/cli/cli/runs/123
 
 .github
 Increase linter timeout from 1min to 3min
 
       
