```bash
user@generic-host:~$ssh vivolev647@generic-host2
The authenticity of host hostname can't be established.
ED25519 key fingerprint is SHA256: 49d180ecf56132819571bf39d9b7b342522a2ac6d23c1418d3338251bfe469c8.
Are you sure you want to continue connecting? (yes/no/[fingerprint])? yes

vivolev647@generic-host2 password:

Linux hostname 7.1.4-13-amd64 #1 SMP Debian 6.12.0 x86-64

The programs included with the Debian GNU/Linux system are free software; the
exact distribution terms for each program are described in the individual files
in /usr/share/doc/*/copyright.

Debian GNU/Linux comes with ABSOLUTELY NO WARRANTY, to the extent permitted by
applicable law.

Last login: Mon Jul 20 12:31:56 2026 from generic-host

vivolev647@generic-host2:~$scp "Documents/vivolev647.gz" user@generic-host:/home/user/Documents
user@generic-host's password:
Documents/vivolev647.gz     100% 67kB 5.2MB/s 00:00
vivolev647@generic-host2:~$exit
logout
Connection to generic-host2 closed.
user@generic-host:~$cd Documents
user@generic-host:~/Documents$ls -a

.  ..  homework  vivolev647.gz

user@generic-host:~/Documents$gunzip vivolev647.gz
user@generic-host:~/Documents$nano vivolev647.md
GNU nano 4.3     vivolev647.md

Hello!
I'm a professional idiot with 15 years' experience in the field of autism.

> "I'm like the Starmer of Computer Science; I say I'm going to write
something, then decide not to."

I use TypeScript, Python, C#, and Lua.

Unlike the fuckwit I stole this README format from (jk lol), I do actually use
linux. I'm too stupid to even install Arch or Gentoo, though.

Half of my code doesn't work because I can't be bothered to maintain it
(or to make it work in the first place, honestly).

Have fun reading my code, because even I don't understand it half the time!
(That's not a good thing, is it?)

^G Help  ^O Write Out  ^W Where Is  ^K Cut  ^T Execute  ^C Location  M-U Undo
^X Exit  ^R Read File  ^\ Replace  ^U Paste  ^J Justify ^/ Go To Line M-E Redo
```
