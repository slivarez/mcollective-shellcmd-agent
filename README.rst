===================================================================
 ``shellcmd agent for mcollective`` -- run arbitrary shell commands
===================================================================

``shellcmd`` is licensed under the GPL, see the file ``COPYING`` for
more information.

``shellcmd`` agent is a very simple agent for running arbitrary shell
commands on your mcollective machines.


Install
=======

- Grab it from github::

    git clone git://github.com/joemiller/shellcmd-agent.git

- Copy ``shellcmd.rb`` to the mcollective agent directory on all 
  of your mcollective-managed machines.

- On your client machine, install the ``mc-shellcmd`` control script by
renaming it to shellcmd.rb and putting it in the application directory

- Test it::

    mco shellcmd 'echo i execute therefore i am'

Do you really want to run the command echo i think therefore i am unfiltered? (y/n): y

===============================================================
HOST:host1.yoursite.com EXITCODE:0 STDOUT:
===============================================================
i think therefore i am
===============================================================
===============================================================
HOST:host2.yoursite.com EXITCODE:0 STDOUT:
===============================================================
i think therefore i am
===============================================================



Finished processing 14 / 14 hosts in 663.52 ms

TODO
====

See the Issues page on github for more: http://github.com/joemiller/shellcmd-agent/issues

Authors
======

Joe Miller, <joeym@joeym.net>, 9/13/2010
Joe McDonagh, <jmcdonagh@thesilentpenguin.com>, 2012-08-16
