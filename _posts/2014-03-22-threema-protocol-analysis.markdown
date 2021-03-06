---
title: Threema protocol analysis
date: 2014-03-22
excerpt: I analyzed the custom protocol used by the mobile messaging application Threema and wrote a paper to summarize my results.
---

I spent the last weeks analyzing the protocol used by the mobile messaging application [Threema](https://threema.ch/en/).
It's a custom protocol with some similarities to [CurveCP](http://curvecp.org/). Just like CurveCP it uses the [NaCl library](http://nacl.cr.yp.to/) to encrypt packets.

You can read about the results of my analysis in [this paper](http://blog.jan-ahrens.eu/files/threema-protocol-analysis.pdf).

During my analysis I focused on understanding the protocol. In [my paper](http://blog.jan-ahrens.eu/files/threema-protocol-analysis.pdf) I'm neither judging whether the protocol includes any weaknesses nor if the application contains some implementation mistakes. Nevertheless, the protocol seems to be well designed.

I'd like to thank [Kasper Systems GmbH](http://www.kaspersystems.ch/), the company behind Threema,
for removing the reverse-engineering paragraph from their [End-User Software License Agreement](https://shop.threema.ch/eula).

I've published [a repository](https://github.com/JanAhrens/threema-protocol-analysis) with the latest version of the paper and the LaTeX source code [on GitHub](https://github.com/JanAhrens).
