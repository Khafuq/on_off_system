# Arduino Auto Switch Off
Switch off EVERYTHING including the Arduino itself

Building on the experiences of recent power-saving videos, I thought I would try as an experiment whether we could switch off the Arduino itself as well as any surrounding circuitry - and then switch it back on again via some external stimulus.

All data sheets, code examples and similar are right here on my GitHub!

Data sheet for typical N-Channel MOSFET (IRLZ44N)                                                      
http://www.irf.com/product-info/datasheets/data/irlz44n.pdf

Data sheet for typical N-Channel MOSFET (IRL3705N)

https://www.infineon.com/dgdl/irl3705n.pdf?fileId=5546d462533600a40153565f29f42532


Data sheet for typical P-Channel MOSFET (NDP6020P)

https://cdn.shopify.com/s/files/1/0174/1800/files/NDP6020P.pdf?7646591425453007768

And it can be done very easily and with minimal external components. Just two MOSFETs (possibly a single MOSFET and an NPN transistor might be enough) and a couple of resistors and we're done.

The circuit and a breadboard example are all included in this video along with some chat about the MOSFET and what you must NOT do to them if they are to survive.

I admit I was feeling pretty pleased with the whole project - until I discovered, pretty much by accident, that this sort of thing has been thought about by others (who knew?) and they have all pretty much come up with the same circuit concept. Darn it! And there was me thinking I was being all creative and original...

But it's an interesting mechanism to save power and we can experiment with the MOSFETs a bit too. You don't HAVE to switch off the Arduino itself - you can use this same circuit to just switch off everything else instead and then put the Arduino into Deep Sleep. We cover this in the video too! Now, there's flexibility for you!
