#Idle Actions
Execute configured Actions if x session is idle for given time.
This script internally uses xprintidle utility from repository.

I was having problem with login.conf on arch linux using bspwm window manager.
I do not use any display manager like SDDM and start session from command line using startx.
I use this script to suspend or hibernate system if no activity on system for given time.


## Usage

Make Script executable

```bash
chmod 755 idleActions.sh
```

Run action only if X session is idle for 60 minutes.

```bash
bash idleActions.sh 60
```

Wait for default idle time then execute actions.

```bash
bash idelActions.sh
```
