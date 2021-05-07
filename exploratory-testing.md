# AST-Exploratory Testing

This is a course that was never really created. Here we've pulled the materials directly from [TestingEducation.org](http://testingeducation.org/BBST/exploratory/), written by Cem Kaner:

## Overview

Twenty-three years ago, I coined the phrase "exploratory testing." I didn't invent the practice but \(as far as I can tell\) I was the first public advocate of it.

As ET has become fashionable, a host of consultants and academics have started writing and speaking about it. Some of them have helped move the concepts of exploration and testing forward in interesting ways. This lecture asks what we know now: What is exploratory testing and how do we do it?

James Bach pointed out the essential characteristic of exploratory testing — the explorer is cognitively present. She actively, purposefully, curiously investigates the software under test, always with the responsibility of deciding, minute by minute, what is the most promising path to whatever she has chosen to investigate. There are no artificial limits on exploration. The tester is free to use whatever sources of information are available, including specifications, technical support records, competitors’ implementations of comparable software, and \(of course\) experiments \(tests\) that reveal information empirically. There are no limits on test techniques that explorers can use—for example, any degree of automation is fine. However, the explorer doesn’t simply rerun old tests and trust that they’ll reveal whatever is interesting. She tests to learn. She will probably scrutinize the behavior of the program as it is tested, looking for new ideas about how it might fail, how it might be further tested or measured, and how useful these tests are at this point in development. Test execution might be automated—thinking is not.

The antithesis of exploration is scripted testing, in which the tester \(or a machine\) follows a set of procedures laid out long ago, comparing the observed behavior with whatever results the test designer considered relevant or interesting back then. The cognition happened back then, not now.

The scope of exploration is the same as the scope of testing itself.

The old definition of testing—execution of a program with the intent of exposing coding errors—is far too narrow. I used to push this definition too, but my work went beyond it and so did the work of most other skilled testers. When the definition doesn’t describe the practice, I think we should value the practice and fix the definition. Here’s what I work from now:

> Software testing is a technical investigation conducted to provide stakeholders with empirical information about the quality of a software product, system or service. 

The investigation includes research necessary to design information-revealing tests and interpret their results, building tools and data sets to make those tests possible, and communication necessary to report results to stakeholders in an effective way. Like any skilled tester, the explorer does all of these. The difference is that the explorer does them in any sequence that is useful, mixing research, design, execution, interpretation, and communication so as to keep exposing new information and keep up with the ongoing changes in market, platform, design, and implementation of the software under test.

The slides provide material for several videos, but we've only completed taping of the first one....

## Slides

* [ET Slides - Incomplete Redesign](./Exploratory%20Testing/slidesASTETIncomplete2021.pdf)
* [ET Slides - Original](./Exploratory%20Testing/slidesBBSTExploring2006.pdf)

## Videos

* [Lecture 1](http://testingeducation.org/BBST/exploratory/BBSTExploring1.wmv)

