<p align="left">
<img src="https://i.imgur.com/t23TXuR.png" height="20%" width="20%" alt="daubert standard"/>
</p>

Introduction

Of the many services we use over the Internet, email is among the most common. In the years since Internet usage began gaining widespread popularity in the 1990s, email has become a primary means of communication for companies, government, and individuals. Consequently, email is one of the most common sources of evidence that a forensic investigator can examine during an investigation.

 

In its simplest form, email forensics consists of analyzing the source and content of an email message, which enables an investigator to identify the sender, receivers, date, and time. As a source of forensic evidence, email has the power to document a suspect's activities with immense detail. Proper email analysis can prove guilt, innocence, or at least that something happened.

 

However, email is not the only way that people communicate electronically. For personal usage, applications such as Facebook Messenger, WhatsApp, and Discord are immensely popular services that allow individuals to exchange messages over the Internet. Meanwhile, in professional environments, applications such as Slack and Microsoft Teams have gained traction as complements and even replacements for email. As with email, digital artifacts left by instant messaging (IM) and chat applications can hold immense forensic value. This is particularly true if it is possible to recover entire databases containing complete conversation transcripts.

 

In this lab, you will perform forensic analysis on a variety of email and IM services, including Outlook, Thunderbird, Slack, and Discord. You will analyze email headers and search for forensic evidence using Paraben's E3.



Lab Overview

SECTION 1 of this lab has three parts, which should be completed in the order specified.

 

    In the first part of the lab, you will perform basic email header analysis.

    In the second part of the lab, you will search for forensic evidence in email using targeted search techniques.

    In the third part of the lab, you will search for forensic evidence in a chat application database.

SECTION 2 of this lab allows you to apply what you learned in SECTION 1 with less guidance and different deliverables, as well as some expanded tasks and alternative methods. You will explore new evidence in different email clients and chat applications.

 

Finally, you will explore the virtual environment on your own in SECTION 3 of this lab to answer a set of questions and challenges that allow you to use the skills you learned in the lab to conduct independent, unguided work - similar to what you will encounter in a real-world situation.



Learning Objectives

Upon completing this lab, you will be able to:

 

    Navigate the structure of common email client databases, including Outlook and Thunderbird.

    Read and understand the contents of email headers.

    Use E3’s Content Analysis function to sort email attachments.

    Use E3’s Advanced Search function to apply custom search filters.

    Navigate the structure of common chat application databases, including Slack and Discord.



Topology

This lab contains the following virtual machines. Please refer to the network topology diagram below.

 

    vWorkstation (Windows: Server 2019)

 

<img src="https://i.imgur.com/OS9S5HV.png" height="20%" width="20%" alt="forensics"/>



Tools and Software

The following software and/or utilities are required to complete this lab. Students are encouraged to explore the Internet to learn more about the products and tools used in this lab.

 

    Paraben's E3



Deliverables

Upon completion of this lab, you are required to provide the following deliverables to your instructor:

 

SECTION 1

 

    Lab Report file, including screen captures of the following:

 

    Happy Reminder email in the Text Viewer and Timestamp in the Properties pane
    IP address of the sender
    List of files in the Graphics category
    Email that references the Big Boss
    Members of the IntricateSolutions workspace
    Channels in the IntricateSolutions workspace
    Conversation contents

 

    Any additional information as directed by the lab:

 

    None

 

SECTION 2

 

    Lab Report file, including screen captures of the following:

 

    Thunderbird Inbox
    Email from Leo Deforest
    Pills evidence and Beverly Gates corresponding as Natasha "Red" Maximoff
    Beverly's Discord friend list
    Lena Goodwin conversation

 

    Any additional information as directed by the lab:

 

    Document the sender's email address, mail server name, and mail server IP address in the Well, Well, Well email header

 

SECTION 3

 

    Lab Report file, including screen captures of the following:

 

    Email thread returned in the search results
    Additional evidence within the Discord database

 

    Any additional information as directed by the lab:

 

    None

<br />
<p align="center">
<img src="https://i.imgur.com/6H3HuKX.jpeg" height="80%" width="80%" alt="forensics"/>
<br />
<br />
<img src="https://i.imgur.com/zjC6kJ4.jpeg" height="80%" width="80%" alt="forensics"/>
<br />
<br />
<img src="https://i.imgur.com/tbFQWCy.jpeg" height="80%" width="80%" alt="forensics"/>
<br />
<br />
<img src="https://i.imgur.com/FemWget.jpeg" height="80%" width="80%" alt="forensics"/>
<br />
<br />
<img src="https://i.imgur.com/xyE1YP5.jpeg" height="80%" width="80%" alt="forensics"/>
<br />
<br />
<img src="https://i.imgur.com/kougV5Q.jpeg" height="80%" width="80%" alt="forensics"/>
<br />
<br />
<img src="https://i.imgur.com/7iRgzUA.jpeg" height="80%" width="80%" alt="forensics"/>
<br />
<br />
<img src="https://i.imgur.com/OgGMrPa.jpeg" height="80%" width="80%" alt="forensics"/>
<br />
<br />
<img src="https://i.imgur.com/oYEcBOf.jpeg" height="80%" width="80%" alt="forensics"/>
<br />
<br />
<img src="https://i.imgur.com/eVtYG8B.jpeg" height="80%" width="80%" alt="forensics"/>
<br />
<br />
<img src="https://i.imgur.com/Z59InMt.jpeg" height="80%" width="80%" alt="forensics"/>
<br />
<br />
<img src="https://i.imgur.com/Y4TSpqE.jpeg" height="80%" width="80%" alt="forensics"/>
<br />
<br />
<img src="https://i.imgur.com/p3IvgYw.jpeg" height="80%" width="80%" alt="forensics"/>
<br />
<br />
<img src="https://i.imgur.com/cqSnB0P.jpeg" height="80%" width="80%" alt="forensics"/>
<br />
<br />
</p>
