## Archive.it

Archive.it is loosely inspired from a librarian who was painstakingly transcribing 100-year-old journals donated by a local family for a special collections project in the Centennial Library at Cedarville University, and the omni-scanner is pretty overtly stolen from Eion Colfer's *The Eternity Code*, the third book of the *Artemis Fowl* series.

The future technology consists of two parts:

1. The omni-scanner
2. Cloud services

At a glance, the omni-scanner is a  scanning device that can use futuristic sensors to digitize anything it scans, and Archive.it is a service that provides users with the means to remotely access their archived files by subscribing to its service. For more information about both, see the [product website](https://suspicious-einstein-85bca5.netlify.app/).

> Note: I wrote the web copy (hence the lower word count here) and deployed the [Hugo](https://gohugo.io/) theme to Netlify. Unfortunately, the shopping cart is still broken, ABSOLUTELY DO NOT actually provide any credit card information. **Neither Archive.it nor its omni-scanner actually exist.**

Interestingly, this fictional device closely tied in with Pederson's question of integrating “digitized historical artifacts with born-digital artifacts” (2020) though the archival purposes of each serve vastly different purposes. Pedersen aspires to chronicle a public progression of technology, drawing from digital humanities and rhetorical studies to consider how humans have and will embody technology. The purpose of the omni-scanner is much less noble and focuses on privately safeguarding memories and purchased content, though in part also limited due to Hollywood-related copyright restrictions. Those same restrictions seem to reiterate Pedersen’s notion of privileging neither “historical nor born-digital representation.” For example, in Spain creating a backup of copyrighted film is completely legal as long as the owner also has access to the original disc (Peng). Therefore, the digital cannot exist (legally) without the physical, within the context of DVDs. Affording more value to the tangible is not a new phenomenon, as exemplified through print newspaper subscriptions versus web news subscriptions (Hussman). However, while Pedersen’s central focus may be on creating egalitarian exhibits, this **imagined product** is more concerned with marketing to the increasingly digital and even digital-native populations. 

## Target audiences and stakeholders

The biggest audience for Archive.it would be millennials and their parents. Millennials grew up watching Disney VHS tapes and listening to cassette tapes but transitioned to both CDs—the optical drive is basically dead now (Kyrnin) so by extension so is the CD—and later mp3s while the Boomers filmed them in VHS, 8mm, or even Betamax. The amount of unplayable-without-specialized equipment media between both generations is staggering. A secondary, but likely equally large, audience is anyone who refuses to pay for the same thing twice. While there are probably collectors who have each *Lord of the Rings* movie on VHS, DVD, Extended DVD edition, and Blu-ray, they’re more likely the exception than rule. This audience is also most likely to [use the omni-sensor to backup their DVDs and Blu-rays](https://suspicious-einstein-85bca5.netlify.app/blog/post-2/) despite the questionable legality. 

The group most concerned with legality would be the movie studios who continue to profit by selling the same old movie with a slightly different label branded as remastered. The broad strokes of the Digital Millennium Copyright Act (DMCA) favor these studios. Circumventing DVD encryption is explicitly illegal (copyright.gov). However, the existing “encryption” is no more secure than the write protect switch on the side of SD cards. In 2001 students at MIT broke DVD encryption with 7 lines of PERL (Guadamuz). 

![SD Write Protection](https://www.diskpart.com/screenshot/en/others/others/move-lock-switch-to-remove-write-protection.png)

Regardless, their lobbying has paid off, and the law currently criminalizes circumventing decryption. 

## Cautionary Steps

Despite this clear illegality, there are potentially two large backdoors.

> Regardless, until the current interpretation of the law changes, devices active in restricted zones as designated by IP addresses will not support archiving commercial DVDs and Blu-rays.

If the omni-sensor is not connected to the internet, it will not have an IP address within any region, so archiving DVDs could work. Rendering any offline scanner into a paperweight would create a poor user experience, but creating region-specific units with different hardcoded functions would be cost-prohibitive to produce. Archive.it could release a patch update that disables DVD functionality when offline but would have no way of enforcing users to install it. Next steps would be to meet with counsel to determine the scope of our liability and and entirely focusing marketing on entirely obsolete mediums that are inherently unencrypted.

The second backdoor is to simply use a VPN when archiving DVDs. A list of countries where backing up DVDs is legal immediately follows the statement of unsupport, effectively signalling the best IP address ranges to spoof to use both the omni-scanner and Archive.it without issue. Moving towards a more nuanced if not completely away from protesting the current state of copyright law interpretation would be a clear step in the right direction. Whether or not Archive.it could be held liable remains unclear, but it’s always safer to err on the side of caution.

An entirely different challenge with this device is that determining ownership only requires possession. There’s nothing to stop someone from scanning a friend’s book or buying/scanning/then returning a stack of books to Barnes and Noble or any other book store. As a measure of good faith, Archive.it could auto-detect library books by recognizing the bar codes and could set an imposed self-destruct where the digitized file would be erased with a certain timeframe unless scanned again. But that system wouldn't work with new books.

Perhaps the omni-scanner could chemically mark or radiate scanned items, and anything marked wouldn’t be able to be scanned again. Archive.it could also develop and sell readers to retailers that verify whether returns have been altered from being scanned, like a counterfeit detector pen but for scanned books or other media. But chemicals and radiation are scary and would definitely prevent this from being a commercially available product. Introducing chemical or radiant “safeguards” just adds needless complications. Commercially available scanners, DSLRs and even the relatively new [xcanex](https://www.kickstarter.com/projects/piqx/xcanex-the-intelligent-book-scanning-station) all have the ability to “scan” and archive books, but with a many more manual steps. There does seem to be a precedent that the manufacturer is not responsible for how customers use their products. 

Additionally, the idea of one-time-only scanning would also prevent people who added additional notes in the margins or highlighted sections from reimporting their new annotations, a key feature highlighted in [Protect your memories](https://suspicious-einstein-85bca5.netlify.app/blog/post-3/). 

## Affordances

While wedding tapes and “baby’s first” albums will always carry sentimentality, the same isn’t necessarily true of the countless drawers filled with forgotten VHS tapes covered in mold, which causes that wobbly effect, or or boxes of overexposed and undeveloped film. Providing people with a way to both access and potentially restore these captured memories (or favorite childhood movies) can help lessen hoarding tendencies by shifting tangible the perceived extension of self or being of a close friend (Yap) from the physical clutter to the relatively intangible digital space. By separating the value from the junk, people can feel able to dispose of or recycle their clutter. Due to legal reasons, Archive.it shouldn’t suggest archiving personal libraries or film collections to take back shelf space, but this messaging is entirely valid for non-copyrighted material.

Actual archivists may also find this technology useful or entirely frustrating. Instead of painstakingly scanning each page of ancient texts or boxes of photographs over the course of weeks, the omni-scanner would allow a very low-effort and zero-contact process, both increasing productivity and reducing the chance of damaging any of the texts. While seemingly a net win, this interaction demonstrates archivists becoming tools of their tools (Norman), losing their ability to practice their craft instead being forced to move books from one location to another, reducing their work to manual labor from a labor of love. 

The ability to preserve all media is still huge affordance. Books become worn, CDs get scratched, photos fade, but their digital counterparts do not. You can’t spill coffee on an ebook, dog year its pages, drop it in a pool. It will always be the same as long as that file exists. Similarly, you can listen to an mp3 file thousands of times without degradation but continual playing can cause CDs to rot (Sydell). As the outer layer erodes, a silver layer becomes exposed, and once exposed, the silver begins to tarnish. While hard drives do fail, Cloud backups have redundancy built in to avoid data loss and  Redundant Array of Independent Disks (RAID) setups are even available to those who want to run their own local backup. Sydell noted that many archivists are still in the process of moving microfilm to CDs. The omni-scanner could allow them to more easily move from both microfilm and CDs to a digital format. Potential next steps may include creating an enterprise-level plan and pricing tier to focus more on more Pedersen-like endeavors to preserve historical information.

However, there could also be unfortunate consequences. This technology could lead to a resurgence of forgotten sex tapes and boudoir shots from unlabbed tapes and undeveloped film. While Cloud-hosted content on Archive.it is only accessible to the registered user, any one performing [local backups](https://suspicious-einstein-85bca5.netlify.app/blog/post-1/) would be able to distribute it. Be it revenge porn or secret footage recorded without consent, this is problematic territory. Archive.it could consider developing its own digital rights management (DRM) tool alongside a desktop application to prevent sharing, but that doesn’t prevent content like this from being put into a more accessible format. Additionally, subjecting user-owned media to DRM could be seen as invasive if not worse, like vendor lock-in or invasion of privacy.

Privacy is especially a concern as many home movies would be of private moments: birthday parties, bath time, vacations, piano recitals, weddings. Actively policing moments that people outside of the family have no business viewing would be both difficult to justify and sell. Moving to a fully automated moderation system may address this concern, but successfully building or training that system would bring about a huge shift to the entire industry; rather, doing would be entirely impossible for a predominantly hardware like Archive.it, especially when larger, specialized companies are still struggling to solve this problem.

Perhaps outsourcing the Cloud storage aspect to Box or Dropbox could limit Archive.it’s responsibility regarding moderating content, but that opens up significant cost that would likely affect the Archive.it’s [current pricing model](https://suspicious-einstein-85bca5.netlify.app/blog/post-4/). As discussed in [Cautionary Steps](#cautionary-steps), camera manufacturers are not held responsible for illegal photographs taken with their equipment. While Archive.it does backup media, it is then only available to the user who backed it up. This limitation may prevent this service from rising to the qualification of Distribution. Using the omni-scanner locally is less clear. The omni-scanner converts media into a more easily distributable format, but plays absolutely no role once individual files are created. Is enabling easier distribution clearly distinct from the act of distributing files? Again, clear next steps are to consult with legal counsel to determine actual liability.

The final issue again returns to copyright. Despite the precedent allowing people to copy songs from their CDs to their iPods, film studios are still actively fighting to protect their copyrights. While this may be a non-starter as streaming becomes more prevalent, their army of lawyers could prevent Archive.it from releasing to the wider market. Archive.it could initially only release its cloud service worldwide but release the omni-scanner in more favorable markets like Sweden or Spain as a proof of concept. However, limiting market share at launch runs the risk of copycat products from competitors. Studios and publishers could also use this time to examine the products and attempt to sue or draft legislation to permanently prevent Archive.it from making its omni-sensor available in the United States. Conversely, releasing somewhere like China could be a better move. The United States is relatively young while a country like China is thousands of years old and literally invented paper. Archive.it would have to learn more about the international archivist community and would likely have to research and support modern to ancient Chinese languages, but could definitely create a much larger impact. The home market may be less of a priority, but perhaps becoming an established niche archival company could later pave the way to break into the home market.  

## Next steps

Regardless, the first next step is to find legal representation to help Archive.it navigate copyright law. Archive.it could likely go ahead with releasing its online Cloud service to those in need of a remote backup, but that’s already a strongly saturated market and doing so likely wouldn’t turn a profit any time soon. Marketing and selling to large libraries and museums would be a good step before releasing omni-scanner products to the wider market.

## References

Bloom, Paul, and Matthew Jordan. “Opinion | Are We All ‘Harmless Torturers’ Now?” The New York Times, August 9, 2018, sec. Opinion. https://www.nytimes.com/2018/08/09/opinion/are-we-all-harmless-torturers-now.html.

Guadamuz, Andrés. “Trouble with Prime Numbers: Decss, Dvd and the Protection of Proprietary Encryption Tools.” SSRN Scholarly Paper. Rochester, NY: Social Science Research Network, July 28, 2004. https://papers.ssrn.com/abstract=569103.

Hussman, Mary Eliza. “Valuing Newspaper Website Content: What People Are Willing to Pay for and Why.” Accessed August 6, 2021. https://doi.org/10.17615/PQBF-2D77.

Kyrnin, Mark. “Why Do Most New PCs Not Come With DVD or Blu-Ray Drives?” Lifewire. Accessed August 6, 2021. https://www.lifewire.com/death-of-the-computer-optical-drive-832403.

“Manage | FreeLogoDesign.” Accessed August 6, 2021. https://www.freelogodesign.org/manager/signin?r=https%3A%2F%2Fwww.freelogodesign.org%2Fmanager%2Fshowcase%2F739ceac63f764583865c1d1cfbcc8c4e.

Shift Credit Card Processing. “No Cost Credit Card Processing for Small Business,” May 10, 2016. https://shiftprocessing.com/no-cost-credit-card-processing/.

Noble, Barnes &. “How to Download EBooks FREE: Over One Million Titles Available|NOOK Book.” Barnes & Noble. Accessed August 6, 2021. https://www.barnesandnoble.com/w/how-to-download-ebooks-free-melissa-lavendier/1124589821.

Norman, Don. The Design of Future Things. Basic Books, 2009.
Owl Loader. Accessed August 6, 2021. https://cdn.dribbble.com/users/1438321/screenshots/3778346/untitled-2.gif.

Peng, Donna. “DVD Digital Copyright Laws in US, UK, Japan, Australia...” Accessed August 3, 2021. https://www.winxdvd.com/resource/dvd-copyright-infringement-laws.htm.

KindPNG.com. “Subscription Icon Png, Transparent Png - Kindpng.” Accessed August 6, 2021. https://www.kindpng.com/imgv/imiRbTi_subscription-icon-png-transparent-png/.

Sydell, Laura. “How Long Do CDs Last? It Depends, But Definitely Not Forever.” NPR.org. Accessed August 6, 2021. https://www.npr.org/sections/alltechconsidered/2014/08/18/340716269/how-long-do-cds-last-it-depends-but-definitely-not-forever.

TeamViewer. “TeamViewer: The Remote Desktop Software.” Accessed August 6, 2021. https://www.teamviewer.com/en-us/.

Copyright.gov. “The Digital Millennium Copyright Act of 1998,” n.d. https://www.copyright.gov/legislation/dmca.pdf.

3D Printing Industry. “The Matter and Form 3D Scanner Is Here!,” September 14, 2014. https://3dprintingindustry.com/news/rejoice-affordable-matter-form-3d-scanner-32946/.

Pngtree. “Vector Vault Icon, Vault Icons, Bank Vault Icon, Safe Icon PNG and Vector with Transparent Background for Free Download.” Accessed August 6, 2021. https://pngtree.com/freepng/vector-vault-icon_3782885.html.

Villains Wiki. “Wan Shi Tong.” Accessed August 6, 2021. https://villains.fandom.com/wiki/Wan_Shi_Tong.

Yap, Keong, and Jessica R. Grisham. “Unpacking the Construct of Emotional Attachment to Objects and Its Association with Hoarding Symptoms.” Journal of Behavioral Addictions 8, no. 2 (June 1, 2019): 249–58. https://doi.org/10.1556/2006.8.2019.15.
