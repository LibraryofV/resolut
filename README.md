# resolute
by Anis Ali Khan
Resolute is my take on the bug tracker that just works.

A decade of IT support on the road, in the datacenter, at headquarters, in the office, at home and with the customer has taught me that bug trackers, ITSM CRM tools, ERP software, ticketing systems and are:

1. Bloated
2. Cumbersome
3. Far more complex than most humans care to actually use
4. Slow
5. Limited in ways that are seemingly obvious to me
6. Complicated to keep up to date
7. Not very satisfying to use
8. Error prone

Case notes: ServiceNow
SNow is one of the more ubiquitous tools on the market for tracking issues in a company.
Yet, there are many things that plenty of free software can already do out of the box that SNow does not do.

Example: iTunes and Chrome have search that finds results as you type. If this is a module that can be used in a commercial application, why is it not used in SNow?
It almost seems to me that an expensive application that requires one or several architects, consultants & developers to effectively implement should at the very least provide search power on par with consumer software. This is not the case with most implementations.

Snow is available on prem and in the cloud. This hybrid availability makes it complicated to continually realease. In practice, most enterprise scale organizations are several versions behind, and the entire process of keeping the software up to date is obscure, opaque to the end user, and basically something end users dread.
I like getting software updates, as in Windows Insider fast ring, which gives you something interesting, kind of exciting and cool to look forward to every time the software is updated. I am going to learn about a new feature. It will be something new, I will get to see how it works. If I like it, if it's something I might use, I will. Right away, and it usually works most of the time.
The update experience for Snow is more along the lines of "did you hear they pushed a new update? Nope. But the system was down for 7 hours on Monday, no wonder." It's an off-putting experience to end users, and this makes them feel disdain and drains any enthusiasm they may have to try some cool new features.
Worse than that, the features are neither obvious, nor consistently documented, nor graphically previewed to the user as they are about to use impacted features of the new version for the first time.
This to me means that an unacceptable degree of enforcing best practices of DevOps culture is being permitted in the architecture of the software.

Lesson learned:
A sound platform as a service should make it either impossible or difficult to do things the wrong way.
It must reward the developer, integrator and end user when they do something the right way.
It must be quick, fault tolerant, highly available, scalable, and feel effortless to use, work on, improve and extend.
The documentation should be consistent, easily digestible and localized autonomously.
When machine translation tools exist to at the very least provide readily available tools to make the system available and consumable in many languages, this should be the norm, rather than some difficult or implausible task to implement.

Case notes: Dynacom

Dyunacom was the first French language accounting application developed for citizens of Quebec to use for accounting in companies trying to computerize their accounting process. The application was developed in VB 6 and to this day remains a VB 6 application that is still in use, but only by 3500 or so companies. The company grew to employ 50-100 people, but the inconsistent documentation practices of the original developers make the software impossible to scale up and scale out now that 20 years have passed in production. To the end that very few developers today still care to write VB 6, and even fewer new developers care to learn what is considered a legacy language.
Furthermore, the software was written in a way that makes it extremely difficult, basically impractical to translate into languages. No one currently employed at that company knows how to even approach this problem. It is considered so costly to even consider that they cannot serve customers from countries where English or French are not the primary spoken languages.
This is a sharp contrast to many Google products, which are typically available in many languages. Even small business websites sometimes are integrated with Google online translation services, allowing anyone to translate their web pages with a single click.
It seems reasonable, logical and desirable that this be ubiquitous for software development today. It is not at all the case.

Case notes: Dynamics

Dynamics is an enterprise resource management software by Microsoft. From inventory management to scheduling, to manufacturing to shipping, to issue tracking, ERP software is expected to be a ubiquitous system in use across all departments of an organization. The software is so complex to the end user, however, that several implementations are concurrently in use and each delivers a more or less adequate experience. Again, observe that this is a software that though extensive in its capabilities, is difficult to adapt to different use cases. Tech support uses it to track cases, but an entire screen of fields that are not necessarily relevant to the end user are simultaneously displayed in a noisy, overwhelming page in the web browser. On the customer service end, RMAs are processed using a different version of the software which has limited licenses and is only accessible through a VM. The software doesnot support copy & paste, though copy & paste are supported in other VMs you may use in the course of your work.

Case notes: Helpdesk Assistant

