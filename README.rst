==========================
mcollective-shellcmd-agent
==========================

run arbitrary shell commands

``shellcmd`` is licensed under the GPL, see the file ``COPYING`` for
more information.

``shellcmd`` agent is a very simple agent for running arbitrary shell
commands on your mcollective machines.


Install
=======

- Grab it from github::

    git clone git://github.com/slivarez/mcollective-shellcmd-agent.git

- Copy content of ``agent`` directory to the mcollective agent directory on all 
  of your mcollective-managed machines.

- Install ``open4`` gem (http://rubygems.org/gems/open4) on all mcollective-managed machines.

- On your client machine, copy the content of ``application`` directory to the mcollective application directory

- Test it::

    mco shellcmd 'echo i execute therefore i am'


TODO
====


Authors
======

- Joe Miller, <joeym@joeym.net>, 9/13/2010
- Joe McDonagh, <jmcdonagh@thesilentpenguin.com>, 2012-08-16
- slivarez, <slivarez@gmail.com>, 2013-10-29
