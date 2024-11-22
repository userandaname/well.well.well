Hiya, this is Zayaan AR.

I have come here to follow up on a previous incident with a user by the display name of "Seifcume", username of "seifcume", and userID of "1029171830973530132", has been going against not only Discord's ToS, but also their Developer ToS as well.

In a jist of things, this user, mainly being their alternative account under the display name of "Cortana 🎗", username of "microsoft_cortana", and userID of "1183599021365932139", has been breaking Discord's ToS, developer ToS, and is also attempting to spread misinformation about AtomLabs services, mainly being our signature bot, Atom, as well as spreading misinformation about one of our partners, Sokora, with their in-development Discord bot to soon arrive to the scene.

I am sending this document on behalf of the Sokora team, and for AtomLabs as a whole, considering I literally own AtomLabs.

I will refer to these users as "Tempus" / "Tempus Fugit", and "Cortana" respectively for context. (Old display name of seifcume was Tempus)

Now that I've explained an introduction for some context, let's get right into the underlying issue.

Firstly, Tempus Fugit owns a bot under the name of Garply. Garply, and thus Tempus Fugit, break Discord Developer ToS by underlying features within their bot which allow for unauthorized code execution which can be used to run raw Python code to attack any server the bot was a part of. This was an .eval command which had been completely undocumented to the consumer, with this execution being locked to Tempus Fugit's userID. I shouldn't have to explain why this is already bad for servers with the bot in it, but in a gist, this allows for any server with the bot in it to be exploited whenever Tempus Fugit likes via running their own Python code on these servers.

Garply, as well as all of Tempus Fugit's bots were entirely run on our servers, as we used to be partners with Tempus Fugit before we knew about all of these major security vulnerabilities.
The second that our team had known about this major security implication that this could have on many servers, we cut ties with Tempus Fugit, and removed their bots from our infrastructure.

We also went ahead and got screenshots as well as message links of all of this happening, with actual evidence showing Garply replying to the eval command with the respective result, where Tempus Fugit attempted to get a server invite link without my consent, as the bot was in one of my testing servers at the time. I had luckily had Security Actions activated, disallowing for any new invite links to be created, and thus Tempus Fugit was unable to get a new invite link to the server. 

This clearly violates the Discord Developer Policy, upon the line located at the end of the Policy, which states:

"Note that we require developers to notify Discord and affected users of potential unauthorized access to API Data, as described in Section 5 of the Developer Terms."

This API Data is clearly being accessed by Tempus Fugit in order to create invites without administrator consent, which is a major violation of the Developer Policy, as these servers could be private servers, not intended for the public to have access to.

Tempus Fugit has unsurprisingly, not notified Discord, nor the affected users of the potential unauthorized access to API Data, and thus further proves that he is in direct violation of the Developer Policy.

He also broke Discord ToS, as he uses a modified version of Discord called "Vencord", which breaks Discord's Platform Manipulation Policy as shown here:

"Don’t modify the Discord client for any reason — including automating account actions or altering the appearance or layout of Discord (https://discord.com/safety/platform-manipulation-policy-explainer#:~:text=Don%E2%80%99t%20modify%20the%20Discord%20client%20for%20any%20reason%20%E2%80%94%20including%20automating%20account%20actions%20or%20altering%20the%20appearance%20or%20layout%20of%20Discord)"

Not only that, but he also had another bot called Mitch, which was a code fork of Garply, which used to be in AtomLabs's support server; Atom Support, as an automated moderation bot, and when we punished him for abusing his moderation powers while he was still one of our partners, he logged into a bot client into Mitch, and used the client UI in order untimehim out, at which point he got caught by me after about an hour, and he thus got banned from Atom Support. Again, screenshots of him owning up to this on his alt account, Cortana, as well as the backdoor being caught within the Audit Log, is all at the end of this message.

Once we took action via removing the bots from our infrastructure, Garply was now being self-hosted, and within this time, we reported such activities, to Discord Support, as well as top.gg.

I spoke to a lovely moderator over at top.gg about the situation, that moderator being Woo (display name: "Woo", username: "_woo_", userID: "136583532972605440"), who got onto the job, and after providing the necessary proof, including messages of him attempting to gain unauthorized access to my development/testing server, and banned Tempus Fugit, and removed both Garply, and his other bot, which is now deleted, called snake, from top.gg permanently.

However, despite contacting and following up with Discord on this matter, we have waited for over 2 weeks for a response, with still no response from a human whatsoever, which is unacceptable to do with such a high risk security vulnerability, why is why we feel the need to now make another support ticket in an attempt to get Tempus Fugit reprimanded for such actions.

If you do wish to give us a response over there, feel free, i'll be keeping an eager eye out for your response ;) (caseID: #49651230)

We personally believe that such activity should be catered to immediately, and if Garply were to be verified, there could've been an even higher server count that could've been exploited by Tempus Fugit, and thus we are now taking further action to ensure that this does not happen again.

Garply, as well as other of Tempus Fugit's bots have since been either deleted or privated, but if we hadn't taken such a high priority matter into our own hands, then it is likely that such behaviour would've continued, and thus be a major security risk to many servers, and their extremely valuable data, which should be protected with the highest standard.

But this isn't even the end of it.

He also made A LOT of alternative accounts, in order to ban evade through to join Sokora's Discord server, where it was painfully obvious that it was one of his alternate accounts, due to them being made on the same day which they joined the server, with no pfp, no badges, no about me, no nothing. Just stupid display names and usernames which made it obvious it was him.

If this wasn't enough, because of me being the main one taking action against him, and making his bots privated because of the severity of the situation, and Discord refusing to take action, Tempus Fugit has also been spreading misinformation about AtomLabs services, mainly being our signature bot, Atom, as well as spreading misinformation about one of our partners, Sokora, with their in-development Discord bot, saying that they were made with AI, which is demonstrably false. However, this communication took place on his alternative account, Cortana, in order to possibly avoid detection by Discord Support, as well as to avoid any potential repercussions that could've been taken against Tempus Fugit.

Such misinformation is not only harmful to our reputation, but also to our partners, as we are a small, indie bot, which is still in development, and thus we are still trying to get our name out there, and such misinformation could potentially harm our reputation, and break consumer trust, leaving our brand, as well as Sokora, in a bad light with consumers and server admins.

Ironically, Garply, as well as the majority of Tempus Fugit's bots, were also made with AI. Even the bot's 2-paragraph description on top.gg was 100% AI generated!
Thus, Tempus Fugit is spreading misinformation about our services, while also using the same technology that he is spreading misinformation about, which we feel is slightly ironic given the circumstances.

We have also managed to gather a few witnesses of Garply being made with AI, as Garply actually used to be completely open-source on GitHub for a short time, before being privated by Tempus Fugit.
Now, you may wonder, why would Tempus private Garply's GitHub repo?

Well, it's because it had been very obviously made with AI, as shown within the AI-generated comments after a lot of the source code of Garply, which actually fueled the fire for him, as this shows just how little Tempus cares about the security of his bots, as well the security of user, or server data that may have also been collected automatically by the bot.

We've also gone ahead and managed to get a few witnesses who actually saw the AI-generated comments, and who have consented to be witnesses in this case, as well as to provide evidence of such comments being made by the AI.
Unfortunately, I was not around to see the AI-generated comments, as I was in the Discord bot development scene at the time when Garply was open-source, so you'll need to rely on these witnesses, and contact them for further questions throughout this.

These witnesses include:
    - Sky (@skycodee, userID: 1131236182899052696)
    - グースさん (@goos.exe, userID: 725985503177867295), (founder of Sokora)

As a reminder, we have attached such screenshots to this message, as well as message links which you'll see further down for further context, and to provide raw evidence of such claims.

In addition, Sky actually confronts Tempus of Garply's bot token being leaked, which is a major security risk in itself, which I won't elaborate on too much, as this note is already extremely long. (for good reason!)

We also discovered that Garply appeared to be doing things, like editing and re-assigning roles, which it interestingly doesn't have functionality to do, and when confronted about all of the features of Garply in some now deleted messages, he refused to elaborate on what functionality the bot had.

We are mainly contacting you in order for some sort of reprimandation to Tempus Fugit/Cortana, as well as to ensure that such behaviour does not continue throughout the future, as we believe that such behaviour is not only harmful to us, but also to the Discord community as a whole, which is why we felt the need to step in and protect your fellow users, while you look into this behaviour in the meantime.

Screenshots are attached below, and message links are just here:
    - https://discord.com/channels/1252393773468745852/1254573705439481856/1295085301391167619 (Tempus attempting to create a server invite to my development server, but failing catastrophically)
    - https://discord.com/channels/1252393773468745852/1254573705439481856/1295085303064952884 (Garply's response to Tempus attempting to create a server invite)
    - https://discord.com/channels/1252393773468745852/1254573705439481856/1295086018407563274 (Tempus tries again...to no success)
    - https://discord.com/channels/1252393773468745852/1254573705439481856/1295086020886528102 (Garply fails yet again)
    - https://discord.com/channels/264445053596991498/325648177178869760/1297680771473084428 (top.gg removing Tempus's bots from their platform)
    - https://discord.com/channels/1252393773468745852/1254573705439481856/1285330002350706708 (Tempus being caught using backdoors/bot clients within Mitch)
    - https://discord.com/channels/@me/1259993380989960223/1285334990434861078 (Tempus caving, confesses to using a bot client)
    - https://discord.com/channels/@me/1259993380989960223/1285335682184773677 (Tempus sending a screenshot of the bot client logged in as Mitch)

If we do find any more evidence of Tempus or Cortana, or any of his other alt accounts, we will keep you updated and add more information after this initial message.

Kind Regards,
Zayaan AR, owner of AtomLabs (https://atomlabs.ie).
