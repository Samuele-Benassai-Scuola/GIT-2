
# GIT - Working with Remotes

* I repository remoti sono versioni del tup progetto che sono ospitate su Internet
* La collaborazione con altri programmatori implica la gestione di questi repository remoti e il push e il pull di dati

Fondamentale è saper **sincrionizzare il nostro lavoro locale con un repository remoto**.


_Comandi principali:_

`git remote -v` --> visualizza i server remoti collegati al nostro repository

### Aggiungere o rimuovere un repository remoto

`git remote add <nome> <url>`

### Caricare il lavoro locale sul repository remoto

`git push <remote> <ramo-locale>`

### Aggiornare la copia locale del repository, allineandola con la versione remota

`git pull <remote> <ramo-locale>`
