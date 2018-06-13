# History of WWIV
***
##The Official History of WWIV 
**By Wayne Bell Random 1@1**  
_Originally posted in WWIVNEWS Volume 1, Issue 1, January 1991_

WWIV started around December 1984, when  I first put up a BBS. It
was run on  an IBM-PC with a 10  meg hard disk and a  Hayes 1200. I was
running  WWIV v1.0,  which was  in interpreted  BASIC. It crawled along
quite slowly, and did not have a whole lot of features.
About the only  other BBSs I was competing with  at the time were
run on Apple II's, also running  in interpreted BASIC. Of course, there
were RBBSs  and the like, but  I do not recall  ever having called one.
Soon the 64k limitation of IBM interpreted BASIC became apparent. I did
some pretty  strange stuff with  memory allocation and  string storage,
but I had pretty much reached the  cutoff point. When you try typing in
30 lines of a  message and the result is an "out  of memory" error, you
know it is time to go on to something better.

The better thing was Turbo Pascal 2.0. Turbo 2.0 did not have ANY
support  directories (all  file I/O  was within  your current directory
only).  I also  had quite  some trouble  getting comm routines working.
With the release  of Turbo 3.0, I put  up WWIV v2.0. Soon after  that I
got  REAL interrupt-driven  comm  routines,  and things  started moving
along.

I had  to go off  to UCLA, and  was forced to  take the BBS down.
Around December  1985 on Christmas vacation,  I decided to put  the BBS
back up for some reason. I did some major revamping at some time around
then,  and called  it WWIV  v3.0. Still  in Turbo  Pascal 3.0,  though.
Around this time (December), I got around to putting in a file section.
It took  quite a bit  of work getting  xmodem working, and  I had to go
back and re-format my data files  to allow for file descriptions. Since
I had never actually  been on any other IBM-type BBS,  I had no clue as
to  how the  file section  should  work,  so things  turned out  pretty
randomly.

On  January 1,  1986 I  finally released  WWIV v3.0.  It ended up
going through  quite a few revisions,  especially in the first  week or
two after being  released. And, to make things even  more fun, I had to
resume classes at UCLA, so I  ended up pretty much writing WWIV without
running a BBS. As you may guess,  this caused a few unfortunate bugs to
slip by me, but that's life.

Sometime around June 1986, I had decided to put in ANSI color and
call it WWIV v3.2. This involved  re-formatting the user list (to store
the user's color  selections), and a few other little  fun things, so I
decided to put up  a BBS again. This was only for  a week because I had
to move  back up to  UCLA after that  time for the  summer session. You
might think  that not many  people would end  up calling a  BBS that is
pretty much stated as  only being up for a week, but  it managed to get
some pretty good  activity. To make this week even  more fun, for about
half of it I was not there. I had a friend of mine, Stephen Davis, call
up and remotely take care of  this experimental BBS. It even managed to
make it without crashing.

After releasing that,  it turned out that I had  a pretty bad bug
in the Y-Modem routine. The BBS would read in a block of data, and THEN
seek  to the  right place  in the  file instead  of FIRST  seeking then
reading. So I came out with 3.20a rather quickly. Around January 1987 I
put up the BBS again, running 3.21d.

Then  around June  1987 I  started writing  WWIV v4.0. Naturally,
since I  had a summer  job, things did  not go so  fast. Also, the fact
that I had never written anything in  my life in C before did not help.
I eventually got the hang of things. Finally,  on Dec 1, 1987, I put up
4.0 as my  BBS for testing in real  life. Among my big promises  of how
great it would be, I said  it would support networking among systems. I
thought this sounded like  a good idea, only I had no  clue as to how I
would  go about  implementing it  at the  time. So  I relegated that to
"don't hold  your breath" status,  secretly thinking I  might never get
around to it.

Surprisingly,  I did  get around  to it  relatively soon. By that
time, everyone had  already installed the BBS on  their computers, so I
was stuck with the  format I had dreamed up a long  time ago when I had
no clue how  it would work -- a number  1-65535 indicating which system
was which. I ended up trying  to design a network around that, although
it was not  quite the optimal solution (as  if is such a thing).  I was
bored one day  and had been talking with someone  about a network, so I
decided  to start  writing a  program to  send files between computers.
There was no planning at all, I  just pretty much sat down and typed it
in. That developed into the NETWORK.EXE program.

Of course, there was more to  it than that. It was actually after
I had the  NETWORK.EXE program mostly  working that I  started thinking
about how the systems would connect together. I originally started with
the idea of having it pretty much hierarchial, with a local-system list
for all  systems to call  directly any systems  that were local.  After
talking with Stephen Davis about this  for a while, I decided to pretty
much  have it  grid-like, with  an amorphous  structure. That does not,
however, prevent some  structure from being applied to  it. Without any
software  changes,  it  can  be  easily  changed  over  to  a  straight
hierarchial structure. All I would have  to do is set up the hierarchy,
change one file, and send out an update of that.

Well that  pretty much brings me  up to the present  time. Future
expansion? Who  knows. One thing  that keeps appearing  is a multi-line
WWIV.  That just  is not   practical. WWIV  depends upon  many external
programs  (chains,   FSED,  archiving  programs)   and  you  can   NOT,
practically, have the BBS run external programs without running under a
multi-tasking  operating  system.  To  put  it  simply,  PC-DOS was not
designed with multi-tasking in mind.

## WWIV Software Services
In January of 1998, Dean Nash purchased WWIV and WWIV Software Services 
from Wayne Bell. WSS was reformed as a Tennessee Limited Liability 
Company with a full corporate posture. Craig Dooley was appointed Support 
Coordinator and supervises the Support Board System and Source Distribution 
Sites.

## WWIV 5 
WWIV 5.0 was started in 1999 with moderate progress which picked up in 
earnest in 2003. On going development and daily build releases continue 
to this day.

On September 18 2004 WSS announced that WWIV 5.0 would be open source 
under the Apache License. Originally the code was managed on 
Sourceforge, but in 2015 development was moved to GitHub.

[Original Open Source Announcement](WWIV_Open_Source_Announcement)

##WWIV Hall of Fame

HOF Member | Handle | Node | Contributions
--- | --- | ---- | ---
Wayne Bell | Random | WWIVnet @1 | The creator of WWIV
Dean Nash | Trader Jack | | WWIV Software Services
Adam Caldwell | The Emporer |  | WWIVEdit
Craig Dooley | | | WWIVToss

## [Other WWIV Pages](links.md)
