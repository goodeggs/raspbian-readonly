# raspbian-readonly

An ansible playbook to take a [Raspberry Pi](http://www.raspberrypi.org/) running a fresh copy of [Raspbian](http://www.raspbian.org/) and modify it for read-only usage using [UnionFS](http://en.wikipedia.org/wiki/UnionFS).

## Prerequisites

* [ansible](http://www.ansible.com/)
* [sshpass](https://gist.github.com/arunoda/7790979)
* a Raspberry Pi running stock Raspbian

## Running

Ensure the IP of your Pi is correctly specified in the `hosts` file (default is 192.168.2.2).  Then run:

```
ansible-playbook playbook.yml
```

That's it!

## Credits

* http://blog.pi3g.com/2014/04/make-raspbian-system-read-only/

