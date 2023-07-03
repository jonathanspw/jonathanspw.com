---
title: "Caught in the Crossfire: Red Hat vs. Rebuilds"
date: "2023-07-02"
---

<!-----

Yay, no errors, warnings, or alerts!

Conversion time: 0.418 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β34
* Sun Jul 02 2023 12:02:31 GMT-0700 (PDT)
* Source doc: Caught in the Crossfire: Red Hat vs. Rebuilds
----->


The recent news of Red Hat’s decision to [stop publishing sources on git.centos.org](https://www.redhat.com/en/blog/furthering-evolution-centos-stream) and its [follow-up](https://www.redhat.com/en/blog/red-hats-commitment-open-source-response-gitcentosorg-changes) with quotes like “we have determined that there isn’t value in having a downstream rebuilder” has sent shockwaves across the open source community.  Many are calling for Red Hat’s head on a pike, and to the contrary many support Red Hat’s decision.

Red Hat has made its position clear, many Red Hat employees have taken to Twitter to express their opinions, and the community has responded as well.  Most rebuilds have posted official statements, but no one from the other side of Red Hat’s argument has responded on a personal level.

Hi, my name is Jonathan Wright.  [I’m the Infrastructure Team Lead for AlmaLinux](https://wiki.almalinux.org/sigs/Infrastructure.html#sig-members), a [Fedora packager, sponsor, and EPEL SIG member](https://fedoraproject.org/wiki/User:Jonathanspw), and CTO of [KnownHost](https://www.knownhost.com/).  I’ve experienced many different emotions over the past week as this situation has developed and I feel that it’s important to have a more personal response to what has transpired instead of just organization-level, PR-friendly statements from rebuilds.  I’m a techie at heart and by no means a writer so be forewarned.

Before I was in any of the aforementioned positions I was a CentOS (non-stream) user starting around RHEL/CentOS 4.  I’d originally entered the open source and Linux world with Red Hat Linux 9 (not to be confused with RHEL 9) and SUSE ~7, both of which my father had box sets of circa ~2003.  I bet those boxes are still in his basement to this day if we’re being honest.

Fast forward to ~2007 and my start with CentOS. It was in pursuit of hosting websites and TeamSpeak servers for gaming clans and groups for myself and others - for free, after having been doing my own website/TeamSpeak hosting for several years at this point.  I wanted to do it because I enjoyed the challenge, I enjoyed learning, and I loved the idea of open source, or at least what I could understand of the concepts at the time.  It was at this point that I knew I wanted to work in server hosting and more importantly, with Linux and open source software.

In 2012 I started with KnownHost, my first “real” job in hosting.  I’d been involved with much smaller shops off and on for many years prior but it was at this moment that I felt that I was on the right track to do what I’d come to love.  To this point I had never contributed back to open source in any appreciable way….or did I?  I wasn’t contributing code upstream, I didn’t know how to get involved in that way.  I guess you could say I was oblivious as I’ve come to learn it’s quite easy to get involved but that’s beside the point.  For those first years of my open source involvement, I was championing open source software, speaking the praises of Red Hat and many other FOSS leaders like Apache, MySQL, etc. that I had experience with.  Is that not enough?  Not everyone can be a developer contributing code for open source.  Not everyone is skilled at writing helpful documentation (I’m definitely not).

In December of 2020, [Red Hat announced the discontinuation of CentOS](https://www.redhat.com/en/blog/centos-stream-building-innovative-future-enterprise-linux) and that only CentOS Stream was to continue - an upstream of RHEL.  As a result, rebuilds like AlmaLinux were spawned with the intent of carrying on the mission of the original CentOS project.

I started loosely getting involved with AlmaLinux pretty early on.  It was a natural fit through my relationship with CloudLinux, who bootstrapped AlmaLinux.  (For the sake of clarity, CloudLinux fully [stepped back](https://blog.cloudlinux.com/why-i-have-decided-to-step-down-from-the-almalinux-os-foundation-board) and ceded control of AlmaLinux to a [community-elected board](https://almalinux.org/blog/first-almalinux-board-election-announces-7-new-seats/) - as was always the plan.)  I was ecstatic, I finally had a real “in” to contribute to the open source community, or so I thought.  On September 13, 2021, the AlmaLinux board officially approved me as the Infrastructure Team Lead.

Through AlmaLinux, I met Carl George and after having spoken quite a bit online, I met him at the Open Source Summit in 2022.  He encouraged me to become a Fedora and EPEL packager - and of course I was interested.  In August of 2022, he graciously [sponsored me](https://bugzilla.redhat.com/bugzilla/show_bug.cgi?id=2106939) into the Fedora packager group and I was off to the races.  After getting comfortable with packaging, I promptly asked to join[ Fedora’s EPEL SIG](https://pagure.io/epel/issue/192) to which I was unanimously accepted.  I later [asked to become and was accepted](https://pagure.io/packager-sponsors/issue/554#comment-834570) as a Fedora packager sponsor with the sole intention of getting more people, especially from within the AlmaLinux community, involved in Fedora and EPEL packaging.

Up until last week’s post from Red Hat I thought I was doing everything right.  After about 20 years around open source, I had finally found my way to directly contribute, through AlmaLinux and Fedora/EPEL packaging.  Last week’s blog post from Red Hat and its follow-up leave me with one burning question: \
\
When did I start adding value?

Realistically I don’t think either post targets me directly or my contributions, but at what point did I become a contributor and of value to the ecosystem?  Was it in 2003, when I began championing open source to anyone that would listen?  Was it after 2012, when I started putting bits and pieces of code on GitHub?  Was it when I wrote my first spec file?  When I started helping maintain widely-used packages like certbot?  Where is the line drawn? Who decides?  Don’t we all start as consumers before we become contributors?

I don’t think it can be argued that I don’t personally contribute to the EL, and open source community as a whole at this point - but it took me nearly 20 years to get here, and without CentOS and AlmaLinux I might have never gotten here, at least not specifically in the Fedora/RHEL ecosystem.  Is that not enough of a case for rebuilds to exist?  How many others have similar stories of only getting involved heavily after experience with rebuilds?  Sure this is hard to quantify, but in open source that shouldn’t matter.  I firmly believe that I only ended up here because RHEL is awesome AND CentOS existed as a free rebuild so I could use the awesome RHEL software, for free, without limitation - by way of CentOS.

This post might make it seem like I hate Red Hat.  I can assure you I don’t, even after the recent blog posts.  Red Hat is a champion of open source and their number of contributions upstream is likely [unmatched](https://www.redhat.com/en/about/open-source-program-office/contributions).  I don’t even hate the people who made the decision to stop publishing sources to git.centos.org. I can’t fault them for acting in a way that they feel is the best for their company, and in their eyes, for open source - even if I disagree.  I have the utmost respect for Red Hat and from a business perspective I can even sympathize with their position.  I’ve met and worked with so many incredible minds at Red Hat through my work with AlmaLinux and Fedora.  I do agree that there are bad actors out there trying to make a quick buck from Red Hat’s hard work, but I disagree that rebuilds are bad, provide no value, or should be eradicated because of this.  I hope this post will resonate with those that were behind this decision to see it from a different perspective and see that it’s impossible to quantify the benefit of rebuilds, but it’s there.  I like to think I’m an example of it.