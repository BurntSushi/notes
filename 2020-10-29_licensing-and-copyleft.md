Software licensing and my opposition to copyleft
================================================
I regularly allow myself to get drawn into discussions on software
licensing, largely because I see the same problematic claims repeated over and
over. Invariably, the discussion leads to the same places with varying results.
So I think it's best to write down my position and answer a few common
rebuttals.

I'll start by saying that I am a rather terrible activist, and I attribute this
to the fact that I see myself as a deeply practical person. While I oppose
all forms of intellectual property, this opposition is rarely practiced. I
regularly publish software that is copyrighted by me. I pay for and consume
copyrighted media. I generally avoid violating copyright. I've even held my
nose and signed a couple patents, because that was the expedient thing to do
and it wasn't a hill I was willing to die on.

In practice, my opposition to intellectual property appears in some very light
advocacy when it comes up and the application of the
[UNLICENSE](https://unlicense.org/)
in as
[many places as possible](https://github.com/BurntSushi/ripgrep/blob/master/FAQ.md#license).
But even that gets pushed aside by practical concerns, as I typically dual
license software under both the MIT and the UNLICENSE, because some folks are
[afraid of the UNLICENSE](https://github.com/BurntSushi/byteorder/issues/26).

My opposition to intellectual property (patents, copyright, trademarks, trade
secrets, etc.) itself comes from both ideological and practical concerns.

Ideologically, it's pretty simple: I don't believe that ideas can be
meaningfully owned as property. That is, I see property as a means to
non-violently resolve conflict over scarce resources. But ideas are not scarce,
and thus, to me, they are not property and thus should not be treated as
property. This is a fundamental assumption on which all intellectual property
rests, and so, I reject it from first principles.

Practically, the courts and policies that make up intellectual property law
have become corrupt, and this can have significant negative consequences around
the world. One of the big ones is the cost of important drugs. But I digress,
[Information Feudalism](https://www.amazon.com/Information-Feudalism-Owns-Knowledge-Economy/dp/1595581227/ref=sr_1_1?dchild=1&keywords=information+feudalism&qid=1604019288&sr=8-1)
covers this in more detail than I ever could. There are of course objections to
this. For example, the lack of monopoly protections might prevent people from
making the drugs themselves, lacking financial incentive. But I've always found
this to be a weak argument, as there are plenty of examples in history of
[people developing important medication even without the reward of monopoly protection](https://en.wikipedia.org/wiki/Jonas_Salk).
Information Feudalism explores this better than I could.

From this opposition, my opposition to copyleft follows simply: copyleft
requires copyright to function, and thus, I oppose it.

**Why oppose copyleft when it is a hack against intellectual property itself?**

A common rebuttal to my opposition to copyleft is that most serious copyleft
proponents are _also_ opponents of intellectual property too (or at least,
oppose copyright). And thus, all that is required is for me to understand this
hack in order to come to my senses and support copyleft as a tactical weapon
against copyright itself. But there are some problems here.

Firstly, if I oppose copyright itself, then is it really okay to use
the same system I oppose against itself? I think "yes" is absolutely a
defensible answer, but I think "no" is as well. It is perhaps analogous to the
stance of a pacifist. With that said, I don't consider myself a pacifist.

Secondly, this somewhat assumes that a world without intellectual property and
a world in which the four software freedoms were codified into law (effectively
making copyleft universal) would be similar worlds. I don't think they would
be. For example, in a world without intellectual property, I would support the
_right_ of persons to publish binary programs while making its source code
obfuscated or impossible to attain. This is a clear violation of
[the four essential freedoms](https://www.gnu.org/philosophy/free-sw.en.html)
as described by the Free Software Foundation. Yet, it would be legal---but
perhaps not ethical---to do it in a world in which intellectual property does
not exist. However, there is a flip side to this: in a world without
intellectual property, users would be free to reverse engineer said programs
without fear of legal reprisal.

Thirdly, there are practical reasons to oppose copyleft. Namely, when I publish
source code, one of my main goals is for as many people as possible to use it,
regardless of whether it's other individuals or giant corporations. Given the
current intellectual property regime, corporations are incentivized against the
use of copyleft software in a large variety of circumstances. Thus, copyleft
software, particularly libraries, is regularly avoided by corporations. Since
some of these corporations also play a huge role in the FOSS world itself, this
leads to systemic network effects that push folks strongly towards the use of
permissive licenses. Thus, putting aside ideology and activism, it is simply a
reality that if I publish a library with a copyleft license, it's less likely
to be used by folks, which is inhibits my goal.

Fourthly, the use of copyleft somewhat implies that my highest goal is the
preservation of the four essential freedoms. But my highest desire is actually
to end intellectual property itself and thus the state's enforcement of
monopoly power.

As I said above, I'm a pretty terrible activist. A good activist is willing to
give things up in exchange for advocacy. But I care more about sharing my code
as much as possible.

**Do you support laws that enshrine software freedom?**

If software freedom is the four essential freedoms as described by the FSF,
then, no, I don't. However, I do support software freedom in the sense that
I would advocate for others to provide that freedom as much as possible. I
might even go as far to say that it would be unethical to deny those essential
freedoms to users. But I would not support laws to enforce them because I don't
think such laws should exist without requiring the notion that ideas can be
owned.

This leads to an important distinction that I draw but that seems routinely
ignored among denizens of the web. Namely, that laws and ethics are not one in
the same. One can be opposed to using a law to inhibit some undesirable
behavior while simultaneously finding that behavior unethical.

A good example of this is plagiarism. I am categorically opposed to plagiarism,
even if the license allows it. But I am also opposed to using laws to inhibit
plagiarism, again, because it requires laws that recognize ideas as property.

This commonly comes up in discussions where folks release software under a
license that allows some bad behavior (like plagiarism) and then complain
when that plagiarism happens. People inevitably respond with some low brow
blame-the-victim nonsense, "well, that's what you get for using a license that
allows it." But this completely neglects the nuance that one might be opposed
to some behavior on ethical grounds but might not want to unleash the full
coercive power of the state on preventing it.

**Why use the UNLICENSE instead of the BSD0 or some other license?**

In principle, I'm okay with any
[copyfree](http://copyfree.org/)
license, because it is in practice as close as you can get to opting out of the
intellectual property system. However, I specifically use the UNLICENSE because
it draws attention to the problems with copyright itself while also itself
being copyfree. Specifically, the first sentence from
[unlicense.org](https://unlicense.org) reads:

> The Unlicense is a template for **disclaiming copyright monopoly interest**
> in software you've written; in other words, it is a template for dedicating
> your software to the public domain.

Thus, there is a flair of activism involved in using the UNLICENSE. That's why
I choose it over other copyfree licenses.
