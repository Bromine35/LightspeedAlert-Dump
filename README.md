# LightspeedAlert-Dump
Dump of Lightspeed Alert Agent for testing reasons only.

This dump uses a publicly leaked key. Please use this for testing purposes only because of the nature of Alert Agent or whatever. It is pretty easy to figure out how to get a dump for a different key but this repo won't have instructions unlike the other one for Lightspeed Filter :)

The actual reports don't work yet because the key I used is bad but used to work - server returns `invalid customer_id or email`. Maybe I'll find another one that works for further testing. The entire request/report is in a JWT and the key is in alert.wasm. Have fun looking for it.
