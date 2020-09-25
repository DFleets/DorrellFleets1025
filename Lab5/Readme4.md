# **Executive Summary**
In this chapter we will be covering flow charts, different aspects/types of networks and cyber security.

## **Lucidchart**
This was my first experience with Lucid art but not my first with flow charts... I don't typically mind writing things down..
But I do feel like this makes things neater looking and more organized. I will probably have to check this out more thoroughly later.

## **Introduction to Networking**
### **Data Transmission**
**Packet** - Is 2. A unit of data.
Packet matches and is related to a "unit of data" because that is essentially what it is. It is the fundamental unit of data transmitted over the internet. 
Making it pretty much the information broken down and sent/received.

**Packet-Switching** - 4. Technology that allows packets of data to be routed based on destination address.
This term matches and is related by the use of a router, which is a device recieves packets of info and then sends them to their destinations.

**IP Address** - 3. Unique identifying number.
An IP address is the identifying number it is the address of whatever device you have connected to the internet.

**DNS** - 5. Directory of IP address common names.
Meaning "Domain Name Server or System..Is a directory of internet websites and returns IP addresses to youu of the host requested.

**Protocol** - 1. Set rules to allow devices to communicate.
Is literally the rules set to govern how network communications take place.


### **NetworkHardware**
**A.** Hubs are not intelligent and can not filter data they only know when a device is connected and copies the data to all ports.
A switch though similar is intelligent an can learn the addresses of devices connected to it and sends the data only to the correct port instead of all.
**B.** Hubs and switches can only send data to their own networks and cannot read IP addresses, unlike a router which can determine if data is for its network or another network.

### **Network Topologies**
**A.** Single point of failure means if the switch or main hub fails the whole network will fail. The topologies that experience this is Star Topologies.
**B.** A infastructure wireless topology connects the switch to a wireless access point. Also you can connect as many wireless access points that you need. 
A wireless mesh topology allows you to connect your wireless access point to other wireless access points without having to run extra cords and are all talking to eachother and does not matter if one goes out because they will simply reroute. Making it the superior topology.

### **Network Design**
My network design is a Wireless Mesh Topology. I choose this because it has a high level of redundancy so if one(or more) was to fail the others would pick up for it and relay the connections all the way back to the modem. Also since it is wireless there are many access points.. So for me it just seemed to be the most logical.. And honestly probably one of the easier ones to set up.

### **NSA/CSS**
The role of the National Security Agency(NSA) in national security is to gain "decision advantage for our nation and allies under all circumstances".
They use cryptologic know how and support to back the armed forces. CSS(Central Security Services) coordinates policy, guidance on things signal intelligent or Cyber security related to ensure military integration.

## **CyberSecurity & Encryption**
### **Information Security Systems**

**A.** Confidentiality- This could affect my job by me having to think about how we are protecting the clients/users. Seeing as there is so much buyer and seller information attached so it needs to be made secure in a way only the people who need to know can reach it.

Integrity-I would have to consider the different permissions allowed to access their particular information. Also who it is that we have given said access to.

Availability-With this one the big consideration comes down to what information is okay to be made available. Or atleast what times it would be okay. So consideration into people's jobs, whats not as sensitive, and what would need to be altered often plays a key role.

**B.** Logging into my bank account, clocking into work, and checking my email are three daily tasks that all require authentication.. Nowadays all of these require multiple forms of identification... My bank account requires passwords and temporary passwords sent to my phone.My job uses an ID swipe and fingerprint on top of an actual password for all accounts that has to change every sixty days or so.. My email is probably the least secure with just a password check unless Im using a different phone. Then it requires an okay from my personal number. The key here is all of these benefit from multi-factor identification some use two forms and some use three.. I dont know any that wouldn't. But if I was to say only they only had one of each I find the best way would be to send a verification check to the users personal device... because it would require you to not only know the passwords to get into the desired places but require you to have the physical device of the user you are trying to impersonate as well.

**C.** ACL(Access Control List) determines which users can read, add, delete, and modify information. An adavantage is ACLs are simple to maintain and understand but they also have the drawback of having to manage each information source separately. Also as the number of resources rise it becomes harder to maintain.
RBAC(Role-Based Access Control)assigns roles and the roles are given access, rather then giving specific users access rights.This allows for simple adminstration and improves security.The only drawback I can possibly see to this is if someone is assigned the wrong role it could possibly give them access to tons of information rather than just a piece of it.

**D.** The interaction between Ciphertext public key and private key is the ability to send encrypted messages, the information is sent and encrypted with the public key.Then it is transmitted through channels with the ciphered key, and at the end it is decrypted with recipients private key.

**E.** We need public key cryptography because it is necessary to keep people who are actively trying to break transmissions from accessing sensitive systems and informations.

### **Cryptography**

**B.** K yknn rcuu vjku encuu- the alphabet shifts over by three causing A to be C and so on... The message is "I will pass this class".

**C.** When I typed my message into the box it pointed out which letters I use the most giving you a pattern to work with. I do believe this could be and would be different in
a different langauge just because Im sure certain ones do not have the same vowels and consonants so even though it could still be used it would take more time to get used to. Especially in a language that has different spellings for terms used males or females.


**D.**  A Polyalphabetic cipher is a multi level cipher used to disguise your letter fingerprint.

**E.** So when I typed this message, and then created a shift word it shifted the lettering of the message according to that of the word I used as a way to encrypt my already coded message changing up my letter pattern and slightly evening it out to make it harder to decipher.


### **Brute-Force**
Brute force is a cryptoanalytic technique that tries every possible key to decrypt the cipher and if it is unsuccessful it just moves to the next.
Kerckoff's principle states that even if everyone knows how the cipher works and someone has the cipher texts that it should still be secure. For me I believe that this means 
even if you have the means to crack it. It should still be secure. So even with a brute force cracker it shouldnt be able to decrypt the messages.

# **Conclusion**
 Todays class covered everything from flow charts to networks and some encryption. We went over different topologies and looked at various ways to increase security of said networks through studying ciphers and various weaknesses.
