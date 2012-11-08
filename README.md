fakepop3d
=========

A POP3 server that only returns a warming message about checking your e-mail insecurely.

The impetus for the idea was to have a piece of software that warned people of the dangers of checking e-mail insecurely on public WiFi hotspots.

I did this to see if I could. It is quite incomplete, but did prove I could write a POP3 server in bash and always send a client the same message.

I leveraged xinetd to do the TCP socket handling.


Perhaps one day I'll add to it, it was pretty fun.
