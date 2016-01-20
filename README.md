**bettercap** is a complete, modular, portable and easily extensible **MITM** tool and framework with every kind of diagnostic
and offensive feature you could need in order to perform a man in the middle attack.

Before submitting issues, please read the relevant [section](http://www.bettercap.org/docs/contribute/) in the documentation.

[![Gem Version](https://badge.fury.io/rb/bettercap.svg)](http://badge.fury.io/rb/bettercap) [![Code Climate](https://codeclimate.com/github/evilsocket/bettercap/badges/gpa.svg)](https://codeclimate.com/github/evilsocket/bettercap) [![Join the chat at https://gitter.im/evilsocket/bettercap](https://badges.gitter.im/evilsocket/bettercap.svg)](https://gitter.im/evilsocket/bettercap?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

<table>
    <tr>
        <th>Version</th>
        <td>1.2.3</td>
    </tr>
    <tr>
        <th>Homepage</th>
        <td><a href="http://www.bettercap.org/">http://www.bettercap.org/</a></td>
    </tr>
    <tr>
        <th>Blog</th>
        <td><a href="http://www.bettercap.org/blog/">http://www.bettercap.org/blog/</a></td>
    <tr>
        <th>Github</th>
        <td><a href="https://github.com/evilsocket/bettercap">http://github.com/evilsocket/bettercap</a></td>
     <tr/>
    <tr>
        <th>Documentation</th>
        <td><a href="http://www.bettercap.org/docs/">http://www.bettercap.org/docs/</a></td>
    </tr>
    <tr>
        <th>Code Documentation</th>
        <td><a href="http://www.rubydoc.info/github/evilsocket/bettercap">http://www.rubydoc.info/github/evilsocket/bettercap</a></td>
    </tr>
    <tr>
       <th>Author</th>
       <td><a href="mailto:evilsocket@gmail.com">Simone Margaritelli</a> (<a href="http://twitter.com/evilsocket">@evilsocket</a>)</td>
    </tr>
    <tr>
        <th>Twitter</th>
        <td><a href="http://twitter.com/bettercap">@bettercap</a></td>
    </tr>
    <tr>
        <th>Copyright</th>
        <td>2015-2016 Simone Margaritelli</td>
    </tr>
    <tr>
        <th>License</th>
        <td>GPL v3.0 - (see LICENSE file)</td>
    </tr>
</table>

Installation
============

**Stable Release ( GEM )**

    gem install bettercap

**From Source**

    git clone https://github.com/evilsocket/bettercap
    cd bettercap
    gem build bettercap.gemspec
    sudo gem install bettercap*.gem

Dependencies
============

All dependencies will be automatically installed through the GEM system, in some case you might need to install some system
dependency in order to make everything work:

    sudo apt-get install ruby-dev libpcap-dev

This should solve issues such as [this one](https://github.com/evilsocket/bettercap/issues/22).

Documentation and Examples
============

Please refer to the [official website](http://www.bettercap.org/docs/).
