---
layout: feature
title: 'Echo'
shortdef: 'is this an echo word or a reduplicative?'
udver: '2'
---

<table class="typeindex" border="1">
<tr>
  <td style="background-color:cornflowerblue;color:white"><strong>Values:</strong> </td>
  <td><a href="#Ech">Ech</a></td>
  <td><a href="#Rdp">Rdp</a></td>
</tr>
</table>

Is this a reduplicative or echo word? Such words occur in Hindi and
other Indian languages. In Hyderabad Dependency Treebank they get
their own part-of-speech tags RDP and ECH, respectively. We do not
want to treat them as separate parts of speech because they could be
assigned a POS independent of their RDP or ECH status (same as the
word that they echo). Perhaps we should merge this also with the
"hyph" feature to something called "compound"?

### <a name="Rdp">`Rdp`</a>: reduplicative

The word is a copy of a previous word. In Hindi, this would add the meaning of distribution ("one rupee each"), separation ("sit separately"), variety, diversity or just emphasis.

* [hi] _<b>कभी - कभी</b>_ = “kabhī - kabhī" = “sometimes", "कभी" =
“kabhī" = “sometimes"; "एक एक" = “eka eka” = “one each”, "एक" = “eka”
= “one”

### <a name="Ech">`Ech`</a>: echo

The word rhymes with a previous word but it is not identical to it and
typically it does not have any meaning of its own. In Hindi it
generalizes the meaning of the previous word and eventually translates
as "or something", "etc." etc.

Examples: [hi] "चाय वाय" = "čāya vāya” = "tea or something” (as in "Have some tea or something.”)