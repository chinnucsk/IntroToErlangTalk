Intro to Erlang for C# Developers=====================Slides and code presented NDC Oslo 2013. Links mentioned---------------* [Assign me a screencast assignment / Ask questions](https://twitter.com/bryan_hunter)* [Distributed Erlang demo (screencast)](http://freshbrewedcode.com/bryanhunter/2012/03/27/intro-to-distributed-erlang-screencast/)* [Debugging Erlang demo (screencast)](http://freshbrewedcode.com/bryanhunter/2011/11/27/debugging-erlang/)* [Erlang of Xen Demo](http://zerg.erlangonxen.org/)* [Download Erlang](http://www.erlang.org/download.html)* Microsoft paper: "[Uniqueness and Reference Immutability for Safe Parallelism](http://research.microsoft.com/pubs/170528/msr-tr-2012-79.pdf)"* [Want a Pluralsight course on Erlang? Vote!](http://support.pluralsight.com/forums/127919-new-course-suggestions/suggestions/2835595-erlang-and-erlang-otp)The awe-inspiring demo script-----------------------------**Shell Fun:*** Assignment* Big add* Matching* Tuples* List comprehensions* Cluster from shell**hello****fizzbuzz****manyproc****hotload****the magic clipboard**Scraps to minimize painful in-demo-typing.	cd('c:/code/IntroToErlangTalk/hotload').		cmd /c "cd /d c:\code\IntroToErlangTalk && start werl -sname cat -setcookie taco"	werl -sname dog -setcookie taco	werl -sname bird -setcookie taco	{unix, linux}	rpc:call(goat@ubuntu,os,cmd,["xdg-open http://tinyurl.com/2g9mqh"]).	{win32,nt}	rpc:call(cat@flask,os,cmd,["start http://tinyurl.com/2g9mqh"]).