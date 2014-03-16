mutt-multiple-crypt-hook
========================

With this patch, you can have multiple crypt-hook instances with the
same pattern (recipient). This allows one to specify multiple key-ids
for a particular pattern (recipient). This comes in handy when one wants
to send encrypted email to a mailinglist with a static set subscribers.

I am maintaining this patch for the development releases of mutt. To use 
this patch, download the version you need from [this list][tags]. 

Credits
-------

This patch was written by [Dale Woolridge][dale-woolridge] for mutt
[versions 1.5.3 to 1.5.6][old-patches]. It was transcribed to mutt
version 1.5.22 by Remco Rijnders.

License
-------

Dale Woolridge didn't mention the license under which he released his
patch to the public. His patches are patches for mutt to enhance its
functionality. They are thus a derivative work. As mutt is GPLv2
licensed, so must derivative works be. I have taken the liberty to
release this patch under a GPLv2 license.

[tags]: https://github.com/rejozenger/mutt-multiple-crypt-hook/tags "Patch versions"
[dale-woolridge]: http://www.woolridge.ca/ "Dale Woolridge"
[old-patches]: http://www.woolridge.ca/mutt/multiple-crypt-hook.html "Old multiple-crypt-hook patches"
