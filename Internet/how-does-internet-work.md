# How does the internet work?

>**Note:** For the rest of this article, we will only talk about physical cables, but wireless networks work the same.

## Simple network

When two computers need to communicate, you have to link them, either physically (usually with an [Ethernet cable](https://en.wikipedia.org/wiki/Ethernet_crossover_cable)) or wirelessly (for example with [WiFi](https://en.wikipedia.org/wiki/WiFi) or [Bluetooth](https://en.wikipedia.org/wiki/Bluetooth) systems). All modern computers can sustain any of those connections.

![Two computers linked together](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work/internet-schema-1.png)

Such a network is not limited to two computers. You can connect as many computers as you wish. But it gets complicated quickly. If you're trying to connect, say, ten computers, you need 45 cables, with nine plugs per computer!

![Ten computers all together](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work/internet-schema-2.png)

To solve this problem, each computer on a network is connected to a special tiny computer called **a router**. This router has only one job: *like a signaler at a railway station, it makes sure that a message sent from a given computer arrives at the right destination computer*. To send a message to computer B, computer A must send the message to the router, which in turn forwards the message to computer B and makes sure the message is not delivered to computer C.

Once we add a router to the system, our network of 10 computers only requires 10 cables: a single plug for each computer and a router with 10 plugs.

![Ten computers with a router](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work/internet-schema-3.png)