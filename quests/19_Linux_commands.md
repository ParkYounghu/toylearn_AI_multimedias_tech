```

~ $ pwd
/home/node
~ $ cd Commands && pwd
/home/node/Commands
~/Commands $ mkdir test && ls
test
~/Commands $ mkdir note && cd note && pwd
/home/node/Commands/note
~/Commands/note $ ..
/bin/sh: ..: Permission denied
~/Commands/note $ cd ..
~/Commands $ mkdir -p images videos docs && ls
docs    images  note    test    videos
~/Commands $ cd docs && cd .. && ls
docs    images  note    test    videos

```