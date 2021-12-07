# Transferring Files

To transfer files in between your local computer and AFS, you can use the `scp` command.

---
**NOTE**

`scp` commands must be executed on your local computer. This means that you will have to exit AFS before transferring files.

---

<br/>

To transfer a file from AFS to your computer use:

```
scp ANDREWID@unix.andrew.cmu.edu:[file path within AFS] .
```

To transfer a file from your computer to AFS use:

```
scp [file path within your computer] ANDREWID@unix.andrew.cmu.edu:[desired file path within AFS]
```