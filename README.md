```
> perl6 -v
This is Rakudo version 2016.12-241-g012850dea built on MoarVM version 2016.12-71-g331a6b43
implementing Perl 6.c.

> perl6 test.p6
No such symbol 'Crust::Handler::HTTP::Server::Tiny'
  in method run at /Users/skaji/src/github.com/skaji/Crust-issue/lib/Crust/Runner.pm6 (Crust::Runner) line 5
  in block <unit> at test.p6 line 5

Actually thrown at:
  in block <unit> at test.p6 line 5
```
