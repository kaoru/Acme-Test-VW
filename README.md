# NAME

Acme::Test::VW - Makes your tests always pass under CI

# SYNOPSIS

    # export PERL5OPT=-MAcme::Test::VW

    use Test::More;
    ok 1 == 2;
    done_testing;

# DESCRIPTION

Acme::Test::VW makes your failing tests pass when running under CI (CPAN Testers, Jenkins, Travis CI etc).

Inspired by [https://github.com/auchenberg/volkswagen](https://github.com/auchenberg/volkswagen)

# AUTHOR

Tatsuhiko Miyagawa &lt;miyagawa@bulknews.net>

# COPYRIGHT

Copyright 2015- Tatsuhiko Miyagawa

# LICENSE

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# SEE ALSO

[https://github.com/auchenberg/volkswagen](https://github.com/auchenberg/volkswagen)

[https://github.com/hmlb/phpunit-vw](https://github.com/hmlb/phpunit-vw)
