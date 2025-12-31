---
title: "Messiah Sing-Along"
author: wqzhao
date: 2025-11-29 17:00:00 -0800
categories: [Music]
tags: [music, news, church]
pin: false
image:
  path: assets/img/2025-11-29-messiah-sing-along-in.jpg
  alt: Messiah Sing-Along at San Dieguito United Methodist Church with a Magnificent Pipe Organ
---

## Preparing the Score
When I bought my ticket for the [La Jolla Symphony Orchestra](https://www.ljsc.org)'s *Messiah*,
I expected a typical concert--sit back, relax, and let the professionals do their thing.
Then, just days before the show, an email dropped: we're singing along!
I've sung in choirs before during my freshman year,
and even auditioned with "For unto us a child is born" from *Messiah* itself,
but a full-on sing-along? This was new territory for me.

First challenge: getting a score.
Renting costs $15, buying $20--but as a broke PhD student, every dollar counts.
Thankfully, the Schirmer edition we needed is in the public domain.
Free PDF from IMSLP? Yes please!

Only problem: my ancient iPad chokes on page turns with heavy PDFs.
Time for some command-line magic:
```sh
gs -sDEVICE=pdfwrite -dCompatibilityLevel=1.4 -dPDFSETTINGS=/ebook \
   -dNOPAUSE -dQUIET -dBATCH \
   -sOutputFile=Handel_Messiah_Schirmer_1912.pdf IMSLP11870-Handel_Messiah_Schirmer_1912.pdf
qpdf --linearize --replace-input Handel_Messiah_Schirmer_1912.pdf
```

The optimized PDF is available here:
[`Handel_Messiah_Schirmer_1912.pdf`](/assets/files/Handel_Messiah_Schirmer_1912.pdf)
(public domain).

## Nervous Arrival

The venue was a 20-minute drive from UCSD, in the coastal town of Encinitas.
[San Dieguito United Methodist Church](https://encinitaschurch.com/) sits on a small hill, with beautiful Spanish-style architecture.

![Exterior of San Dieguito United Methodist Church](/assets/img/2025-11-29-messiah-sing-along-out.jpg)

I walked in feeling pretty confident.
That lasted about 30 seconds.
Almost everyone already had their scores out--worn, annotated, clearly well-loved from years of singing.
And here I was with just my iPad.

Found the Tenor section, grabbed a seat.
The guy on my right looked *serious*, handwritten notes all over his score, total pro vibes.
But the couple on my left? Super friendly!
We got talking about how music enriches our lives, how their kids gravitated toward different genres instead of classical.
Their advice: "Sing as loud as you can. Don't worry about mistakes. Fake it until you make it!"
They even showed me a program from 20 years ago tucked into their score. Twenty years of this tradition! That's incredible.

## Rehearsal

To my surprise, there was a warm-up session before the performance.
The conductor ran us through scales--just like my college choir days, but instead of a piano,
we had this *magnificent* pipe organ backing us.
We rehearsed a few key pieces, including tips on "For unto us a child is born"
(keep it lively and joyful!), and learned when to stand and sit based on the conductor's cues.
I used my Apple Pencil to mark up the score on my iPad, finally, a proper use for digital annotations!

## Performance Time

It was challenging.
The basses were right behind to me, singing at full volume--hard not to get pulled off course!
I held my own for most of it, though I did get lost in the score a couple times.

We only sang Part I of *Messiah*, which is apparently standard for sing-alongs.
But then--the moment everyone waits for--the *Hallelujah* chorus.
Of course, that's exactly when I fumbled swiping to the right page on my iPad.
Good thing I had most of it memorized!

Overall? I'm pretty happy with how I did.
The orchestra was compact but every instrument brought that authentic Baroque sound.
The soloists were fantastic.
And there's something magical about a whole room, professionals and amateurs alike, creating Handel's masterpiece together.

## Burger Time

After all that singing, I was hungry.
What better way to end an evening of Baroque music than with some In-N-Out?
I grabbed a window seat with a view of the church on the hill, still glowing in the evening light.
Handel and a Double-Double--a surprisingly great combination.

![In-N-Out Burger after Messiah Sing-Along](/assets/img/2025-11-29-messiah-sing-along-in-n-out.jpg)

I would definitely do this again if given the chance!
