## Archive.it

Archive.it is loosely inspired from a librarian who was painstakingly transcribing 100-year-old journals donated by a local family for a special collections project in the Centennial Library at Cedarville University, and the omni-scanner is pretty overtly stolen from Eion Colfer's *The Eternity Code*, the third book of the *Artemis Fowl* series.

The future technology consists of two parts:

1. The omni-scanner
2. Cloud services

At a glance, the omni-scanner is a  scanning device that can use futuristic sensors to digitize anything it scans, and Archive.it is a service that provides users with the means to remotely access their archived files by subscribing to its service. For more information about both, see the [product website](https://suspicious-einstein-85bca5.netlify.app/).

Ironically, this fictional device closely tied in with Pederson's question of integrating “digitized historical artifacts with born-digital artifacts” (2020) though the archival purposes of each serve vastly different purposes. Pedersen aspires to chronicle a public progression of technology, drawing from digital humanities and rhetorical studies to consider how humans have and will embody technology. The purpose of the omni-scanner is much less noble and focuses on privately safeguarding memories and purchased content, though in part also due to Hollywood-related copyright restrictions. Those same restrictions seem to reiterate Pedersen’s notion of privileging neither “historical nor born-digital representation.” For example, in Spain creating a backup of copyrighted film is completely legal as long as the owner also has access to the original disc (Peng). Therefore, the digital cannot exist (legally) without the physical, within the context of DVDs. Affording more value to the tangible is not a new phenomenon, as exemplified through print newspaper subscriptions versus web news subscriptions (Hussman). However, while Pedersen’s central focus may be on creating egalitarian exhibits, my imagined product is more concerned with marketing to the increasingly digital and even digital-native populations. 

## Target audiences stakeholders

The biggest audience for Archive.it would be millennials and their parents. Millennials grew up watching Disney VHS tapes and listening to cassette tapes but transitioned to both CDs—the optical drive is basically dead now (Kyrnin) so by extension so is the CD—and later mp3s while the Boomers filmed them in VHS, 8mm, or even Betamax. The amount of unplayable-without-specialized equipment media between both generations is staggering. A secondary, but likely equally large, audience is anyone who refuses to pay for the same thing twice. While there are probably collectors who have each *Lord of the Rings* movie on VHS, DVD, Extended DVD edition, and Blu-ray, they’re more likely the exception than rule. This audience is also most likely to [use the omni-sensor to backup their DVDs and Blu-rays](https://suspicious-einstein-85bca5.netlify.app/blog/post-2/) despite the questionable legality. 

The group most concerned with legality would be the movie studios who continue to profit by selling the same old movie with a slightly different label branded as remastered. The broad strokes of the Digital Millennium Copyright Act (DMCA) favor these studios. Circumventing DVD encryption is explicitly illegal (copyright.gov). However, the existing “encryption” is no more secure than the write protect switch on the side of SD cards. In 2001 students at MIT broke DVD encryption with 7 lines of PERL (Guadamuz). 

![SD Write Protection](https://www.diskpart.com/screenshot/en/others/others/move-lock-switch-to-remove-write-protection.png)

Regardless, their lobbying has paid off, and the law currently criminalizes circumventing decryption. 

## Cautionary Steps

Despite this clear illegality, there are potentially two large backdoors.

> Regardless, until the current interpretation of the law changes, devices active in restricted zones as designated by IP addresses will not support archiving commercial DVDs and Blu-rays.

If the omni-sensor is not connected to the internet, it will not have an IP address within any region, so archiving DVDs could work. Rendering any offline scanner into a paperweight would create a poor user experience, but creating region-specific units with different hardcoded functions would be cost-prohibitive to produce. Archive.it could release a patch update that disables DVD functionality when offline but would have no way of enforcing users to install it.

The second backdoor is to simply use a VPN when archiving DVDs. A list of countries where backing up DVDs is legal immediately follows the statement of unsupport effectively signalling the best IP addresses to spoof to use both the omni-scanner and Archive.it without issue. Moving towards a more nuanced if not completely away from protest. Whether or not Archive.it would be held liable remains unclear, but it’s always safer to err on the side of caution.

## Affordances

While wedding tapes and “baby’s first” albums will always carry sentimentality, the same isn’t necessarily true of the countless drawers filled with forgotten VHS tapes covered in mold, which causes that wobbly effect, or or boxes of overexposed film. Providing people with a way to both access and potentially restore these captured memories (or favorite childhood movies) can help lessen hoarding tendencies by shifting tangible the perceived extension of self or close friend (Yap) from the physical clutter to the relatively intangible digital space.

Actual archivists may also find this technology useful or entirely frustrating. Instead of painstakingly scanning each page of ancient books over the course of weeks, the omni-scanner would allow a very low-effort and zero-contact process, both increasing productivity and reducing the chance of damaging any of the texts. While seemingly a net win, this interaction demonstrates archivists becoming tools of their tools (Norman), losing their ability to practice their craft in favor of moving a book from one location to another. 

However, copyright aside, this technology could lead to a resurgence of forgotten sex tapes. While Cloud-hosted content on Archive.it is only accessible to the registered user, any one performing local backups would be able to distribute it. Be it revenge porn or secret footage recorded without consent, this is problematic territory. Archive.it could consider developing its own digital rights management (DRM) tool alongside a desktop application to prevent sharing, but that doesn’t prevent content like this from being put into a more accessible format. Additionally, subjecting user-owned media to DRM could be seen as invasive if not worse, like vendor lock-in or invasion of privacy.

Privacy is especially a concern as many home movies would be of private moments: birthday parties, bath time, vacations, piano recitals, weddings. Policing moments that people outside of the family have no business viewing would be both difficult to justify and sell. Moving to a fully automated moderation system would address this concern, but successfully building or training that system would bring about a huge shift to the entire industry; rather, doing would be entirely impossible for a predominantly hardware like Archive.it. Perhaps outsourcing the Cloud storage aspect to Box or Dropbox could limit Archive.it’s responsibility regarding moderating content, but that opens up significant cost that would likely affect the Archive.it’s [current pricing model](https://suspicious-einstein-85bca5.netlify.app/blog/post-4/). 




