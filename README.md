```
> perl6 -v
This is Rakudo version 2016.12-241-g012850dea built on MoarVM version 2016.12-71-g331a6b43
implementing Perl 6.c.

> perl6 test.p6
No such symbol 'C::B'
  in method run at /Users/skaji/src/github.com/skaji/Crust-issue/lib/C/A.pm6 (C::A) line 5
  in block <unit> at test.p6 line 5

Actually thrown at:
  in block <unit> at test.p6 line 5
```
