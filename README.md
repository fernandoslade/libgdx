# Libgdx

Libgdx is a cross-platform Java game development framework based on 
OpenGL (ES) that works on Windows, Linux, Mac OS X, Android, your
WebGL enabled browser and soon iOS.

#### [Official Site][1]
#### [Issues Tracker (Google Code)][3], include a link to your pull request if applicable
#### [Wiki (Google Code)][4]

#### [Forum][5] Come here to ask questions about Libgdx
#### Join us on irc.freenode.net, #libgdx
#### Follow us on Twitter [@badlogicgames][6]
#### Follow our [blog][2] for the latest updates

## Compiling the Code

This project has a few [prerequisites][7] but primarily uses the ant
build tool. If you wish to compile the Java code then just:

    <checkout code or fetch updated code>
    cd /path/to/libgdx
    ant -f fetch.xml
    ant

And it should compile.  This will
generate a .zip archive of the build and an unpacked "dist" directory.

The "ant -f fetch.xml" fetches the latest native library bits from the
libGDX nightly builds.  This should be done in tandem with fetching
new sources or when updating an existing repository to the latest
bits.

Compiling the native libraries locally is more work.  See the
documentation elsewhere.

You do not need to compile either the native or Java portions of the
library.  You can use libGDX directly from the released or nightly
builds provided.


## Examples

There are a number of example games in the source. Some of them include:

 - metagun
 - superjumper
 - gdx-vertorpinball
 - rtm
 - very angry robots

To see how to use libgdx you can either go to the [wiki][4] (which has plenty of good information) or read through
these example projects. Once again, if you get stuck just drop in to the friendly [forums][5].

 [1]: http://libgdx.badlogicgames.com
 [2]: http://www.badlogicgames.com
 [3]: http://code.google.com/p/libgdx/issues
 [4]: http://code.google.com/p/libgdx/wiki/TableOfContents
 [5]: http://www.badlogicgames.com/forum
 [6]: http://www.twitter.com/badlogicgames
 [7]: http://code.google.com/p/libgdx/wiki/Prerequisits
