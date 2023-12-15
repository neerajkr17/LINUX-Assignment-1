# Linux commands:-

**Ls - List files and directories in the current directory.**

**Cd- Change directory.**

**Touch- Create empty files** 

**Cp- Copy files or directories.**

**Rm- Remove files or directories.**

**Mv- Move or rename files or directories.**


1. # How to make a directory.

Mkdir - The mkdir command is used to create a new directory (folder) in a file system. You can use the mkdir command in a terminal or command prompt on various operating systems.

```
mkdir neeraj
```

```
neeraj\@neeraj-G3-3500:\~$ mkdir neeraj

neeraj\@neeraj-G3-3500:\~$ ls

Commerce                                  Music

Desktop                                   myimage

Dockerfile                                neeraj

Documents                                 Pictures

Downloads                                 Public

E                                         PycharmProjects

get-docker.sh                             snap

google-chrome-stable\_current\_amd64.deb    Templates

google-chrome-stable\_current\_amd64.deb.1  trivy\_0.21.0\_Linux-64bit.deb

linux\_signing\_key.pub                     Videos
```

![](https://lh7-us.googleusercontent.com/bfYAipzqY8HMqr8lMFYfEb0YVgtFnfQzDZla7wo57BKZhmngnh507xFfFwLD6jF3bMjDB4EY__RCJEgh8lOn5lrkuwKT_TSCO563Wa_CCjqSNkyZJWwQdfDmX-zRGeQUbf6LEV-01TjlmtG9Lnqbnt4)

2. # Remove a directory


rmdir- It is used to remove a directory.

```
rmdir neeraj
```

```
neeraj\@neeraj-G3-3500:\~$ rmdir neeraj

neeraj\@neeraj-G3-3500:\~$ ls

Commerce                                  Music

Desktop                                   myimage

Dockerfile                                Pictures

Documents                                 Public

Downloads                                 PycharmProjects

E                                         snap

get-docker.sh                             Templates

google-chrome-stable\_current\_amd64.deb    trivy\_0.21.0\_Linux-64bit.deb

google-chrome-stable\_current\_amd64.deb.1  Videos

linux\_signing\_key.pub
```

![](https://lh7-us.googleusercontent.com/4Rpp7ALVGlADigykojtVz_btYegbUcGQ5--Y-Cv83nHs_a9XFbSwt_yTMRDyBEyXws-X2ZjNvPS3YSEu0nxFmwLxsBMyNK6jp6Z82lrIxWQ9MFoLwipvtQuiei6QMaVZpZx92i3O525EFnY-s9Hwr-M)

3. # Make a copy of a file

```
neeraj\@neeraj-G3-3500:\~$ mkdir work

neeraj\@neeraj-G3-3500:\~$ cd work/

neeraj\@neeraj-G3-3500:\~/work$ mkdir neeraj

neeraj\@neeraj-G3-3500:\~/work$ touch file1.txt

neeraj\@neeraj-G3-3500:\~/work$ ls

file1.txt  neeraj

neeraj\@neeraj-G3-3500:\~/work$ cp file1.txt neeraj/

neeraj\@neeraj-G3-3500:\~/work$ ls neeraj/

file1.txt

neeraj\@neeraj-G3-3500:\~/work$
```

![](https://lh7-us.googleusercontent.com/Bn0vmCZ6HnHMvvfR2fWQianDSZhvoxlWxOfLCwe_u7efRYjMyMpYQA2ampaJMmmRzkvx3v7n3dmn0UwhrmpvPV97TIKA52NUqlvRmCMANReY_noNb-mJuRppLHu8PQt73WljFOS4aButFgLI3QU4HH0)

4. # Move or rename a file

```
neeraj\@neeraj-G3-3500:\~$ ls

Desktop                                   Music

Dockerfile                                myimage

Documents                                 Pictures

Downloads                                 PycharmProjects

emptyfile                                 snap

get-docker.sh                             trivy\_0.21.0\_Linux-64bit.deb

google-chrome-stable\_current\_amd64.deb    Videos

google-chrome-stable\_current\_amd64.deb.1  work

linux\_signing\_key.pub

neeraj\@neeraj-G3-3500:\~$ cd snap/

neeraj\@neeraj-G3-3500:\~/snap$ ls

chromium  node     pycharm-community          snap-store

firefox   postman  snapd-desktop-integration

neeraj\@neeraj-G3-3500:\~/snap$ cd 

neeraj\@neeraj-G3-3500:\~$ cd work/

neeraj\@neeraj-G3-3500:\~/work$ ls

file1.txt  neeraj

neeraj\@neeraj-G3-3500:\~/work$ pwd

/home/neeraj/work

neeraj\@neeraj-G3-3500:\~/work$ cd

neeraj\@neeraj-G3-3500:\~$ mv emptyfile /home/neeraj/work

neeraj\@neeraj-G3-3500:\~$ ls

Desktop                                   Music

Dockerfile                                myimage

Documents                                 Pictures

Downloads                                 PycharmProjects

get-docker.sh                             snap

google-chrome-stable\_current\_amd64.deb    trivy\_0.21.0\_Linux-64bit.deb

google-chrome-stable\_current\_amd64.deb.1  Videos

linux\_signing\_key.pub                     work

neeraj\@neeraj-G3-3500:\~$ cd work/

neeraj\@neeraj-G3-3500:\~/work$ ls

emptyfile  file1.txt  neeraj

neeraj\@neeraj-G3-3500:\~/work$ mv emptyfile neerakfile

neeraj\@neeraj-G3-3500:\~/work$ ls

file1.txt  neeraj  neerakfile

neeraj\@neeraj-G3-3500:\~/work$
```

![](https://lh7-us.googleusercontent.com/ADh6wkUnatmym0-QEpVNgDmZYAM5sl5FG58ogyubx77xg36ZCcP2zN9YABJfLF1cPqpSC74WH9SOX5QeSJ6axBy0atNFR1IW33VMdxnAz1-7iDw1mHH3FnVOODnfn_GPyH2xQLyG15nibLO0fMN4SkE)

5. # Create an empty file

```
neeraj\@neeraj-G3-3500:\~$ touch emptyfile

neeraj\@neeraj-G3-3500:\~$ touch emptyfile

neeraj\@neeraj-G3-3500:\~$ ls

Commerce                                  linux\_signing\_key.pub

Desktop                                   Music

Dockerfile                                myimage

Documents                                 Pictures

Downloads                                 Public

E                                         PycharmProjects

emptyfile                                 snap

get-docker.sh                             Templates

google-chrome-stable\_current\_amd64.deb    trivy\_0.21.0\_Linux-64bit.deb

google-chrome-stable\_current\_amd64.deb.1  Videos
```

![](https://lh7-us.googleusercontent.com/oziKEP9zJLTTz4URfyN-hu_EHX3uuoy2ZKmEbBJm3zPe3PoID9zizaJpdBKaYfWYfP3QgD8Lcx-tj8LsXecOt26yp5IdrjumICrV_VOFqmk8O3b4ypR6onPHQQ8KKmnnRf6KtaGe0GEdK0_sfgI8iVc)

6. # Remove multiple files with a single command

```
neeraj\@neeraj-G3-3500:\~$ touch a.txt b.txt c.txt d.txt e.txt f.txt g.txt h.txt

neeraj\@neeraj-G3-3500:\~$ ls

a      c         Desktop     d.txt      e.txt  get-docker.sh                             h      k                      Music    p                q     t                             v       x

a.txt  Commerce  Dockerfile  e          f      google-chrome-stable\_current\_amd64.deb    h.txt  l                      myimage  Pictures         r     Templates                     Videos  y

b      c.txt     Documents   E          f.txt  google-chrome-stable\_current\_amd64.deb.1  i      linux\_signing\_key.pub  n        Public           s     trivy\_0.21.0\_Linux-64bit.deb  w       z

b.txt  d         Downloads   emptyfile  g      g.txt                                     j      m                      o        PycharmProjects  snap  u                             work

neeraj\@neeraj-G3-3500:\~$ rm a.txt b.txt c.txt d.txt e.txt f.txt g.txt h.txt

neeraj\@neeraj-G3-3500:\~$ ls

a  Commerce  Dockerfile  e          f              google-chrome-stable\_current\_amd64.deb    i  l                      Music    o         Public           r     t                             u       w     y

b  d         Documents   E          g              google-chrome-stable\_current\_amd64.deb.1  j  linux\_signing\_key.pub  myimage  p         PycharmProjects  s     Templates                     v       work  z

c  Desktop   Downloads   emptyfile  get-docker.sh  h                                         k  m                      n        Pictures  q                snap  trivy\_0.21.0\_Linux-64bit.deb  Videos  x

neeraj\@neeraj-G3-3500:\~$
```

![](https://lh7-us.googleusercontent.com/0TTJMJGcb-1sloInzHIt4uCCJanXuvw8QcPcDtk-PTTpv26gheyNAQp3oVUTYoY2F1MrMBNrgZ-xzxEOrVU6xXrRMWdFCvMWa6rqPCosj5r2qoVifpt3Jhl_6IwumfaTp9F6sGk_Ud0l2iWvSczoFlI)

7. # Remove content from the folder without removing folder

```
neeraj\@neeraj-G3-3500:\~$ ls

Desktop                                   Music

Dockerfile                                myimage

Documents                                 Pictures

Downloads                                 PycharmProjects

get-docker.sh                             snap

google-chrome-stable\_current\_amd64.deb    trivy\_0.21.0\_Linux-64bit.deb

google-chrome-stable\_current\_amd64.deb.1  Videos

linux\_signing\_key.pub                     work

neeraj\@neeraj-G3-3500:\~$ cd work/

neeraj\@neeraj-G3-3500:\~/work$ ls

file1.txt  neeraj  neerakfile

neeraj\@neeraj-G3-3500:\~/work$ pwd

/home/neeraj/work

neeraj\@neeraj-G3-3500:\~/work$ cd

neeraj\@neeraj-G3-3500:\~$ rm /home/neeraj/work/neerakfile

neeraj\@neeraj-G3-3500:\~$ cd work

neeraj\@neeraj-G3-3500:\~/work$ ls

file1.txt  neeraj

neeraj\@neeraj-G3-3500:\~/work$ 
```

![](https://lh7-us.googleusercontent.com/dpgUOTGxXov8fC5zSRhm7jnXj-Ae57scrAGsJsgTRfwr8kl0nKpPXAG5KJ9_zFoKykasmltKoPCmbrcAcJgBsSrxZSIQLfJM1oFF2lMd_HWLGowO-MjChgOnsmgXUMzkITHwm9eFtyKT7ZVYyhtRXOg)

8. # Create multiple folder(a-z) with a single command

mkdir:- this command is used to make a directory.

{a..z}:- This is a brace expansion in the shell. It generates a sequence of values between 'a' and 'z'.

Brace expansion in the shell is a feature that allows you to generate a sequence of text or values by specifying a range or a list within curly braces { }.

```
mkdir {a..z}

ls
```

```
neeraj\@neeraj-G3-3500:\~$  mkdir {a..z}

neeraj\@neeraj-G3-3500:\~$ ls

a                                         Music

b                                         myimage

c                                         n

Commerce                                  o

d                                         p

Desktop                                   Pictures

Dockerfile                                Public

Documents                                 PycharmProjects

Downloads                                 q

e                                         r

E                                         s

emptyfile                                 snap

f                                         t

g                                         Templates

get-docker.sh                             trivy\_0.21.0\_Linux-64bit.deb

google-chrome-stable\_current\_amd64.deb    u

google-chrome-stable\_current\_amd64.deb.1  v

h                                         Videos

i                                         w

j                                         work

k                                         x

l                                         y

linux\_signing\_key.pub                     z

m
```

![](https://lh7-us.googleusercontent.com/nCMLnSkay826OX24UdVsEHVe2iD8Fzi1gI09ghxtRViQUkYURpNjkBUSugdEswOWc9gOtfhKL93JdXKTwFKudDZgVm5IfHPFBNjvJRHCFiCZMchNq0Fq2181SUJpgW0xoJuDQHbkYS1lxqCVWKtmhmg)
