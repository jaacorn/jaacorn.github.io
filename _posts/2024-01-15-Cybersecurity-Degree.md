---
layout: "post"
title: "Self Paced Cybersecurity Degree"
categories: blog school
---

This is my custom list of courses, tools, and topics you should learn to supplement a cybersecurity degree. It is mostly free, with some of the courses being paid to get the certification, but free to audit, and the third party certifications costing from $300-$1200.


## Prerequisites

None! This list assumes you are an absolute beginner, and can only go up. If you already have some experience, you can skip the pieces you know, or breeze through them to get the cert/green check.

> You may find some of the timelines are challenging follow if you have no experience with computers, programming, or cybersecurity in general.
{: .prompt-info }
&nbsp;
<hr>

## Networking

Course | School | Duration | Effort | Frequency | Prerequisites
:-- | :--: | :--: | :--: | :--: | :--:
Network+ | CompTIA | 1.5mo | 20hr/wk | self-paced | CompTIA A+
OR | 
CCNA | [ITPro.tv](https://www.itpro.tv/) | 4wks | 10hrs/wk | self-paced | Network+ or experience with networking
[Wireshark Masterclass](https://youtu.be/DAtyzE1TUlI) | Chris Greer | 1wk | 10hrs | self-paced | none

Networking is perhaps the most important foundation of cybersecurity. You may be able to break into the field, but you won't go far without a solid understanding of TCP/IP, network protocols, DNS, packet sniffing, etc. It is very difficult to comprehend security threats, or even develop your own tools without knowing how computers talk to each other.

I listed both the Network+ and CCNA as an option. The CCNA is far more comprehensive than the Network+, but either should suffice to get a good handle on the basics. Wireshark is a very valuable tool for dissecting network packets, and Chris Greer's tutorials are a great resource to learn it.

## Operating Systems

Course | School | Duration | Effort | Frequency | Prerequisites
:-- | :--: | :--: | :--: | :--: | :--:
A+ | CompTIA | 4wks | 20hr/wk | self-paced | none
Administering Windows Server | [Microsoft Learn](https://learn.microsoft.com/en-us/training/courses/az-800t00) | 4wks | 20hrs/wk | self-paced | Experience with Windows Server (projects, basic setup, etc)
Linux+ | CompTIA | 4wks | 10hrs/wk | self-paced | none

While networking may be considered more important, knowledge of the machines you are working on is actually the first step. Intimate knowledge of Windows, Linux, and server OSs' is definitely a requirement.

The A+ from CompTIA is a great starting place for someone with no experience. If you understand Windows, but are looking to get into Linux, I recommend throwing together a virtual machine and building a Linux box. Practical experience will always be more helpful than book knowledge. In saying that, the Linux+ is on this list because its been recommended as a great way to learn the  nitty gritty of Linux so you are prepared no matter what.

## Programming & Scripting

Course | School | Duration | Effort | Frequency | Prerequisites
:-- | :--: | :--: | :--: | :--: | :--:
[Python for Everyone](https://www.coursera.org/specializations/python) | University of Michigan | 8mo | 4hrs/wk | self-paced | none
[OvertheWire (bash)](https://overthewire.org/wargames/) | Online Wargames | 2wks | 8hrs/wk | self-paced | none
[UndertheWire (powershell)](https://underthewire.tech/) | Online Wargames | 2wks | 8hrs/wk | self-paced | none
Linux Shell Scripting | [ITPro.tv](https://www.itpro.tv/) | 2wks | 10hrs/wk | self-paced | none
Powershell Skills | [ITPro.tv](https://www.itpro.tv/) | 6wks | 10hrs/wk | self-paced | UndertheWire

Ah yes, what everyone thinks of when you say you work in tech. Programming. The level of programming competence we are striving to be at is minimal at first. I recommend learning a language such as Python, great for scripting and automation, and a relatively easy language to pick up.

Powershell is also a very powerfull scripting language that is prevalent on all Windows machines, and can be installed on Linux machines. Knowing how to read and dissect basic scripts is the first step on your programming journey. With added time and dedication, you will have the ability to write custom scripts to aid you in your endeavors.

## Labs & Projects

Project | Effort | Description | Prerequisites
:-- | :--: | :--: | :--:
Active Directory Lab | 10hrs/wk | Create a working AD setup from home using virtualization. Start from scratch, build, configure, test, break, and learn how Active Directory works | Network+
Home Network | 60hrs | Ditch your ISP modem/router/ap and build your own network with your own equipment. Firewall, switch, aps, servers, DMZ, etc. | Network+
[Programming Projects](https://github.com/EONRaider/100-redteam-projects) | 5hrs/wk | Hone your programming skills using EONRaider's list of 100 Redteam Projects | Python for Everyone
[TryHackMe](https://tryhackme.com/) | 8hrs/wk | Test your abilities to think outside the box and crush challenges on TryHackMe | none
[PicoCTF](https://picoctf.org/) | 4hrs/wk | Make problem-solving second nature with hundreds of short challenges through PicoCTF | none
[HacktheBox](https://www.hackthebox.com/) | 8hrs/wk | Step up your CTF skills with some more challenging CTFs | TryHackMe
Personal Blog | 6hr/wk | Build a blog/personal website to host walkthroughs, write-ups, and more to showcase your knowledge and investment in the cybersecurity community | none

There is a lot to be said for labs and personal projects. Experience is the single best skill to build when getting into a new career or learning any new skill. Labs and projects will be that experience for you. Building your own AD environment, standing up a SIEM and honeypot, putting your knowledge into action in real-life scenarios with hackable VMs...these practices will cement your knowledge and highlight your weaknesses. 

Programming projects gives you real experience in building solutions to problems; solutions that you can keep around to re-use or modify at your next challenge.

&nbsp;
<hr>

# Advancing Beyond the Basics

At this point, you should have a very well rounded foundation in cybersecurity, with experience in networking, troubleshooting, programming, hacking, and building your own projects and solutions to problems. Those skills are invaluable.

This next section is the step beyond, moving more into the niche category of what you want to do. These are mostly certifications, which can start to cost alot of money. While I don't think you necessarily need most or even many of these certifications, they will help your resume stand out, and get you that chance to show how much you know.

## Pentesting

Course | School | Duration | Effort | Frequency | Prerequisites
:-- | :--: | :--: | :--: | :--: | :--:
Security+ | CompTIA | 1.5mo | 10hrs/wk | self-paced | none
eJPT | [INE](https://ine.com/) | 3wks | 10hrs/wk | self-paced | none
PNPT | [TCM Security](https://certifications.tcm-sec.com/) | 4wks | 10hrs/wk | self-paced | eJPT
Pentest+ | CompTIA | 1.5mo | 8hrs/wk | self-paced | Security+
eCPPT | [INE](https://ine.com/) | 4wks | 10hrs/wk | self-paced | PNPT
OSCP | Offensive Security | 1.5mo | 10hrs/wk | self-paced | eCPPT

Security+ is almost a necessity for any cybersecurity job. It is a door opener for the beginner. Beyond that, there are Red team and Blue team certs (below) to pick through depending on what you want to do.

I really like INE Security's certifications for penetration testing, so I listed several, as well as the infamously difficult OSCP.

## Blueteaming

Course | School | Duration | Effort | Frequency | Prerequisites
:-- | :--: | :--: | :--: | :--: | :--:
eCTHP | [INE](https://ine.com/) | 4wks | 10hrs/wk | none
eCDFP | [INE](https://ine.com/) | 5wks | 10hrs/wk | none
eCIR | [INE](https://ine.com/) | 4wks | 10hrs/wk | none
eEDA | [INE](https://ine.com/) | 5wks | 10hrs/wk | none

These Blue team certs are alot more diverse in subject matter; eCTHP (threat hunting), eCDFP (digital forensics), eCIR (incident response), and eEDA (defense administrator).

Both this section and the previous are dependant on what career path you wish to follow. I wouldn't recommend getting multiple of each just to have them. Specializing in one area will gain you more value than having a shallow knowledge in each specific field.

## Practical Experience

Project | Effort | Description | Prerequisites
:-- | :--: | :--: | :--:
[TraceLabs](https://www.tracelabs.org/) | 10hrs/wk | Develop your OSINT skills working in real-world scenarios, volunteering for a good cause | none
[Bugcrowd](https://www.bugcrowd.com/) | 12hrs/wk | Learn Web Application pentesting by diving into bug bounties. Theres a chance to earn some $ too if you're good | none

Enough cannot be said for practical experience. These are only two options, but internships are a great way to gain experience as well. If you are interested in web application pentesting, I highly recommend working on some bug bounty programs. Not for the money, but for the real-world knowledge you will gain from trying and failing, and trying harder. That is what learning is all about, and pentesting certainly requires a high-level of "no quit".

## Conclusion

This list is certainly not comprehensive, and is constantly changing with the times and your personal goals. It was created as a guide to keep myself in line with my goals, and hopefully encourage others in the same position to pursue their goals in a concise and efficient way.

You can find the entire list on my github here: [Self Paced Cybersecurity Degree](https://github.com/jaacorn/cybersecurity_degree). Hopefully it is helpful to you, and please feel free to message me for any questions or insights on the subject.