# Haskell Document
I've studied haskell for 3 years in my university. I'm gonna write here what I learnt and start haskell career.

# Getting started

## Set up environment

### By GHCup
```
Set-ExecutionPolicy Bypass -Scope Process -Force;[System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072;Invoke-Command -ScriptBlock ([ScriptBlock]::Create((Invoke-WebRequest https://www.haskell.org/ghcup/sh/bootstrap-haskell.ps1 -UseBasicParsing))) -ArgumentList $true
```

### By Native package manager (windows shell)

#### Install choco
```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

#### Install GHC (Glasgow Haskell Compiler)
```
choco install ghc
```

#### Install Cabal (Cabal installation tool for managing Haskell software)
```
choco install cabal
```

#### Install Stack (cross-platform program for developing Haskell projects)
```
choco install haskell-stack
```


### The Haskell Tool Stack
https://get.haskellstack.org/stable/windows-x86_64-installer.exe