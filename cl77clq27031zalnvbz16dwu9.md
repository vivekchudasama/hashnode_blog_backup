## How does the Internet work?🤨

# How does the Internet work?

- Before you start your web development journey You will have to learn the basics of the technical infrastructure of the Web and the difference between the Internet and the Web.
- [MDN](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work)
- [Vivek Chudasama](https://vivekchudasama.com/)
------------------------------------------
# The Internet

- The **Internet** is the backbone of the Web, the technical infrastructure that makes the Web possible. At its most basic, the Internet is a large network of computers that communicate altogether.

- [The history of the Internet is somewhat obscure](https://en.wikipedia.org/wiki/Internet#History). It began in the 1960s as a US-army-funded research project, then evolved into a public infrastructure in the 1980s with the support of many public universities and private companies. The various technologies that support the Internet have evolved, but the way it works hasn't changed that much: The Internet is a way to connect computers altogether and ensure that, whatever happens, they find a way to stay connected.

------------------------------------------------------------------

## A simple network
- At the point when two PCs need to impart, you need to connect them, either truly (normally with an Ethernet link) or remotely (for instance with Wi-Fi or Bluetooth frameworks). All advanced PCs can support any of those associations.

![Simple Network](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work/internet-schema-1.png)

- Such an organization isn't restricted to two PCs. You can interface however many PCs as you wish. Yet, it gets muddled rapidly. Assuming you're attempting to interface, say, ten PCs, you want 45 links, with nine fittings for each PC!

![](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work/internet-schema-2.png)

- To tackle this issue, every PC in an organization is associated with a unique small PC called a switch. This switch has just a single work to do: like a signaler at a railroad station, it ensures that a message sent from a given PC shows up at the right objective PC. To make an impression on PC B, PC A should send the message to the switch, which thus advances the message to PC B and ensures the message isn't conveyed to PC C.

- When we add a switch to the framework, our organization of 10 PCs just requires 10 links: a solitary fitting for every PC and a switch with 10 fittings.

![](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work/internet-schema-3.png)

# A network of networks
- Everything looks OK. Yet, what might be said about interfacing hundreds, thousands, billions of PCs? A solitary switch can't scale that far, yet, assuming you read cautiously, we said that a switch is a PC like some other, so what holds us back from interfacing two switches together? Nothing, so we should do that.

![](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work/internet-schema-4.png)

- By associating PCs to switches, then switches to switches, we can scale vastly.

![](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work/internet-schema-5.png)

- Such a network comes near what we call the Internet, yet we're missing something. We assembled that network for our motivations. There are different networks out there: your companions, your neighbors, and anybody can have their network of PCs. Yet, it's not exactly imaginable to set links up between your home and the remainder of the world, so how might you deal with this? Indeed, there are now links connected to your home, for instance, electric power and phone. The phone framework as of now interfaces your home with anybody on the planet so it is the ideal wire we want. To interface our network to the phone framework, we want a unique piece of gear called a modem. This modem diverts the data from our network into data sensible by the phone framework as well as the other way around.

![](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work/internet-schema-6.png)

- So we are associated with the phone framework. The following stage is to send the messages from our network to the network we need to reach. That's what to do, we will associate our network with an Internet Service Provider (ISP). An ISP is an organization that deals with a few unique switches that are connected and can likewise get to other ISPs' switches. So the message from our network is helped through the network of ISP networks to the objective network. The Internet comprises this entire framework of networks.

![](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work/internet-schema-7.png)

# Tracking down PCs

- To make an impression on a PC, you need to indicate which one. Hence any PC connected to a network has a novel location that recognizes it, called an "IP address" (where IP represents Internet Protocol). It's a location made of a progression of four numbers isolated by dabs, for instance, 192.168.2.10.

- That is fine for PCs, yet we people struggle with recalling that kind of address. To make things simpler, we might moniker an IP at any point address with an intelligible name called a space name. For instance (at the hour of composing; IP locations can change) google.com is the area name utilized on top of the IP address 142.250.190.78. So utilizing the space name is the simplest way for us to arrive at a PC over the Internet.

![](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work/dns-ip.png)

# Intranets and Extranets

- Intranets are private networks that are limited to individuals from a specific association. They are usually used to give an entry to individuals to safely get to shared assets, team up, and convey. For instance, an association's intranet could have pages for sharing an office or group data, shared drives for overseeing key reports and records, entries for performing business organization errands, and cooperation devices like wikis, conversation sheets, and informing frameworks.

- Extranets are the same as Intranets, aside from the open all or part of a confidential network to permit imparting and cooperation to different associations. They are normally used to securely and safely share data with clients and partners who work intimately with a business. Frequently their capabilities are like those given by an intranet: data and record sharing, cooperation devices, conversation sheets, and so on.

- The two intranets and extranets run on a similar sort of framework as the Internet and utilize similar conventions. They can hence be gotten to by approved individuals from various actual areas.

![](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work/internet-schema-8.png)

# Creadit

[MDN Article On How the Internet Work](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work)