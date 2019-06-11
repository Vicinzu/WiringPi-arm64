# wiringPi-arm64

## Note
This is a arm64 fork of the unofficial mirror of WiringPi to support ports (Python/Ruby/etc).

Please do not email Gordon if you have issues, he will not be able to help.

Pull-requests are not currently accepted, since this is a mirror.

For support, comments, questions, etc please join the WiringPi Discord channel: https://discord.gg/SM4WUVG

## How to usse

Just compile like the original wiringPi and install it.

In addition create a fake cpuinfo as /etc/wiringPi/cpuinfo with entries for Hardware and Revision, eg:
```
  Hardware	: BCM2710
  Revision 	: a020d3
```

## wiringPi README

Please note that the official way to get wiringPi is via git from
git.drogon.net and not GitHub.

ie.

  git clone git://git.drogon.net/wiringPi

The version of wiringPi held on GitHub by "Gadgetoid" is used to build the
wiringPython, Ruby, Perl, etc. wrappers for these other languages. This
version may lag the official Drogon release.  Pull requests may not be
accepted to Github....

Please see

  http://wiringpi.com/

for the official documentation, etc. and the best way to submit bug reports, etc.
is by sending an email to projects@drogon.net

Thanks!
