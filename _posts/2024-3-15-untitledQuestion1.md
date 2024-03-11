# Q: What types of malicious behavior can you achieve by knowing a device's MAC Address?

>[!CAUTION]
>Disclaimer: I'm a student who is new to IT and learning about network security as one of my topics of study. This information is to help you protect yourself and others from malicious activity, it is **not** to be used for your own malicious intent. *This content is the result of answering my own question through my own research.*

Last month I took Hack The Box Academy's course: *Intro To Networking*. While reading the portion on IP and MAC Addresses, (both of these addresses are used to identify a device on a network) I started to ask myself, what can *I* do once I have someone/another device's MAC Address? If a MAC Address identifies someone on a network, what happens if I can change my MAC Adddress to identify as somebody else?

The portion of the material that generated this question from **HTB: Academy** was this:
>The device with the matching IP address responds with its own MAC address, and the two devices can then communicate directly >using their MAC addresses

and

>When a device on a LAN wants to communicate with another device, it sends a broadcast message containing the destination >IP address and its own MAC address.

Here's how I answered the question:

### What is a MAC Address?

In short, for a device to connect to a network, it requires a **network interface card (NIC)**, I won't go into detail here about that but the NIC is assigned the MAC Address by the manufacturer. So this address does not change, unlike an IP Address on a network *which does.*

MAC stands for Media Access Control. It's a 12 digit hexadecimal number that is often displayed with a colon seperating each octet (every two digits).  You can even have multiple MAC Addresses on your device, one for each NIC which connects to the network via ethernet or WiFi.

*Again, these are just basics so if you don't understand something, I recommend looking it up because it'll provide a better scope for your undestanding in the sections below. Furthermore, there is just tons of interesting cogs that play into this whole system of IT. So google what an octet is, and its role in Internet Protocol and come back.*

### What can I do if I have somebody elses MAC Address?

<!-- simple expln: https://www.reddit.com/r/AskReddit/comments/792myk/what_can_a_hacker_do_with_our_mac_address/ -->
<!-- detailed expln: https://dongknows.com/mac-address-explained/ -->

<!-- notes: the above link is all well and done but what about when I start messing with the router, and the broadcast message it sends? -->



 <!-- section: finding a mac address https://slts.osu.edu/articles/whats-a-mac-address-and-how-do-i-find-it/ -->






