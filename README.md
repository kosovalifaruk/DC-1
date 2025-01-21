# Pentesting Lab Practices

Vulnerable Machines
DC-1
DC-2 
DC-3


------------------------------------- DC-1 -------------------------------------


DC-1 is vulnerable machine that contains variety of vulnerabilities in order to practice for cybersecurity certficiation exams.

# **Description

DC-1 is a purposely built vulnerable lab for the purpose of gaining experience in the world of penetration testing.

It was designed to be a challenge for beginners, but just how easy it is will depend on your skills and knowledge, and your ability to learn.

To successfully complete this challenge, you will require Linux skills, familiarity with the Linux command line and experience with basic penetration testing tools, such as the tools that can be found on Kali Linux, or Parrot Security OS.

There are multiple ways of gaining root, however, I have included some flags which contain clues for beginners.

There are five flags in total, but the ultimate goal is to find and read the flag in root's home directory. You don't even need to be root to do this, however, you will require root privileges.

Depending on your skill level, you may be able to skip finding most of these flags and go straight for root.

Beginners may encounter challenges that they have never come across previously, but a Google search should be all that is required to obtain the information required to complete this challenge.

# **Technical Information

DC-1 is a VirtualBox VM built on Debian 32 bit, so there should be no issues running it on most PCs.

While I haven't tested it within a VMware environment, it should also work.

It is currently configured for Bridged Networking, however, this can be changed to suit your requirements. Networking is configured for DHCP.

Installation is simple - download it, unzip it, and then import it into VirtualBox and away you go.

# **Important

While there should be no problems using this VM, by downloading it, you accept full responsibility for any unintentional damage that this VM may cause.

In saying that, there shouldn't be any problems, but I feel the need to throw this out there just in case.

------------------------------------- DC-2 -------------------------------------

# **Description

Much like DC-1, DC-2 is another purposely built vulnerable lab for the purpose of gaining experience in the world of penetration testing.

As with the original DC-1, it's designed with beginners in mind.

Linux skills and familiarity with the Linux command line are a must, as is some experience with basic penetration testing tools.

Just like with DC-1, there are five flags including the final flag.

And again, just like with DC-1, the flags are important for beginners, but not so important for those who have experience.

In short, the only flag that really counts, is the final flag.

For beginners, Google is your friend. Well, apart from all the privacy concerns etc etc.

I haven't explored all the ways to achieve root, as I scrapped the previous version I had been working on, and started completely fresh apart from the base OS install.

# **Technical Information

DC-2 is a VirtualBox VM built on Debian 32 bit, so there should be no issues running it on most PCs.

While I haven't tested it within a VMware environment, it should also work.

It is currently configured for Bridged Networking, however, this can be changed to suit your requirements. Networking is configured for DHCP.

Installation is simple - download it, unzip it, and then import it into VirtualBox and away you go.

Please note that you will need to set the hosts file on your pentesting device to something like:

192.168.0.145 dc-2

Obviously, replace 192.168.0.145 with the actual IP address of DC-2.

It will make life a whole lot simpler (and a certain CMS may not work without it).

If you're not sure how to do this, instructions are here.

# **Important

While there should be no problems using this VM, by downloading it, you accept full responsibility for any unintentional damage that this VM may cause.

In saying that, there shouldn't be any problems, but I feel the need to throw this out there just in case.

------------------------------------- DC-3 -------------------------------------

