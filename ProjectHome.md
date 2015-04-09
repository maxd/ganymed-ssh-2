# Ganymed SSH-2: Java based SSH-2 Protocol Implementation #

The Ganymed SSH-2 library allows one to connect to SSH servers from within Java programs. It supports SSH sessions (remote command execution and shell access), local and remote port forwarding, local stream forwarding, X11 forwarding, SCP and SFTP. There are no dependencies on any JCE provider, as all crypto functionality is included.

The latest version also features a basic, preliminary SSH-2 server implementation.

Ganymed SSH-2 for Java was the de-facto standard for open source based SSH communication in Java software for many years. The library is used in many industrial products but also in open source software, e.g., in the widely used SVN plugin for Eclipse.

Originally, Ganymed SSH-2 for Java was developed for the Ganymed replication project at ETH Zurich, Switzerland, back in 2005. In the meantime, its clearly structured code has been ported by different people to other languages as well. Confusingly, there are also Java branches with slightly different names. **However, Ganymed SSH-2 for Java is the original implementation with a stable interface that is backwards compatible to the first implementation written in 2005 (!).**


---


## Documentation ##

Ganymed SSH-2 for Java features Javadoc documentation in outstanding quality as well as a FAQ and example code that covers most features of the software. The source code is clearly structured and emphasizes on clarity and thread safety. The protocol architecture implemented by the library is documentated in [RFC 4251](http://www.ietf.org/rfc/rfc4251.txt).

**Please read the documentation and the supplied example code carefully. Note that Ganymed SSH-2 for Java is open source software provided to you "AS-IS". There is no kind of support being offered.**

The javadoc documentation covers all the functionality found in Ganymed SSH-2 for Java. Hint: to start with, read the documentation for the _Connection_ class, then dig deeper.

## License ##

The Ganymed SSH-2 for Java library is released under a BSD style license.
The Java implementations of the AES, Blowfish and 3DES ciphers have been
taken (and slightly modified) from the cryptography package released by
[The Legion Of The Bouncy Castle](http://www.bouncycastle.org).

## Trademarks ##

SSH is a registered trademark of SSH Communications Security Corp in the United States
and in certain other jurisdictions. Java and J2ME are trademarks or registered trademarks of Sun Microsystems, Inc. in the United States and other countries.
All other names and marks are property of their respective owners.