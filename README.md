# broadcast

This package implements multi-listener broadcast channels for the Go
programming language.

It is a fork of github.com/tjgq/broadcast, the main addition being
the "RegisterListener(chan interface{}) method, so that listeners
can supply their own channel to the Broadcast struct, rather than 
it constructing than and handing out a chan.

Install with `go get github.com/aktungmak/broadcast`.

