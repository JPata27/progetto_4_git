# Git - Working with Remotes

  * I repository remoti sono versioni del tuo progetto che sono ospitate su internet
  * La collaborazione con altri programmatori implica la gestione di questi repository remoti e il push e il pull di dati

Fondamentalmente è saper **sincronizzare il nostro lavoro locale con un repository remoto.**

*comandi principali:*

`git remote -v` --> visualizza i server remoti collegati al nostro repository

### Aggiungere o rimuovere un repository remoto
`git remove add <nome> <url>`

### Caricare il lavoro locale sul repository remoto
`git push <remote> <ramo-locale>`

### Aggiornare la copia loale del repository, allineandola con la versione remota
`git pull <remote> <ramo-locale>`
