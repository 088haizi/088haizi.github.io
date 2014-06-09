---
layout: post
title: "Programming_Ruby_01"
date: 2014-06-10 00:21:39 +0800
comments: true
categories: 
---
### 鸣谢

第一届国际 Ruby 交流会有 32 人参加。我们所有人只在一个小酒吧里聊了一晚上就散了。而现在一切都变了。年会的几百张门票在几个小时内便售罄，而越来越多的扩充会议也如春笋般出现，以满足那些无法来到 Ruby 年会的人的需求。

随着社区的发展，Ruby 当然也在发展。现如今这门语言以及它的库相比这本书的第一个版本发布时已经增长了许多倍。

而这门书也随着这门语言一同在成长。PickAxe 如今已经十分庞大，主要因为我始终希望为每一个内置类（built-in class），模版（module）及方法（method）提供文档说明。但书到了这个体量就绝不可能只完成这一个任务。这个版本是建立在前两个版本基础之上的，这其中的主要贡献来自 Chad Fowler 和 Andy Hunt。严格意义上说，这三个版本都是 Ruby 社区的产物。在邮件列表，在论坛以及在本书的勘误页面，数以百计的人们贡献着想法，代码以及更正使这本书得以趋于完善。我想我始终需要为你们做过以及正在做的事情，向你们每个人说声“谢谢”。Ruby社区如今仍然是令人激动，有趣并且（大多数情况下都）友好，就像它曾经一样。这也正是在高速成长中取得的令我们十分为欣喜的成果。

为这第三次（十周年）印刷，Wayne E. Seguin 承担下了校验关于我们了不起的工具 RVM 的部分，而 Luis Lavena 则校验关于在 Windows 环境下运行 Ruby 的部分。我个人认为应当将 Anthony Burns 称为英雄，为其对于在我编写过程中的更新与变化所做的惊人的工作。而他实际上本身就是个英雄。

使这本书最终的出版同样是个挑战，Kim Wimpsett 是这世界上最好的排版编辑，她是我知道的唯一一个能找到代码中的错误并能修复 XML 文档结构的排版编辑。任何本书中最终的错误都是我的手误打错了她的矫正导致的。另外，归功于 Janet Furlow 的督促，才使我们得以赶在第十届 Ruby 年会之前出版。

最后，我仍须由衷感谢松本行弘，Ruby 的创造者。在这长期而艰难的成长与变化中，他在推广这门语言中始终表现的友善，令人振奋并乐于献身。（Throughout this prolonged period of growth and change, he has remained helpful, cheery, and dedicated to polishing this gem of a language.）Ruby 社区中这种友善与开放的精神正是他的个人魅力的直接映射。

感谢你们所有人。Domo arigato gozaimasu.

-------

Dave Thomas

The Pragmatic Programmers

<dave@pragprog.com>

June 2013

下面是原文

-------
<br>

### Acknowledgments

The first International Ruby Conference had something like 32 attendees. We could all fit into the tiny hotel bar and talk the night away. Things have changed. The annual conference now sells out many hundreds of seats within hours, and an increasing number of secondary conferences have sprung up to meet the needs of folks who can’t get to RubyConf.

As the community has grown, so has Ruby. The language and its libraries are now many times bigger than they were back when the first edition of this book came out.

And as the language has grown, so has this book. The PickAxe is now massive, mostly because I still want to document every single built-in class, module, and method. But a book of this size can never be a solo undertaking. This edition builds on the work from the first two editions, which included major contributions from Chad Fowler and Andy Hunt. Just as significant, all three editions have been works created by the Ruby community. On the mailing lists, in the forums, and on this book’s errata pages, hundreds of people have contributed ideas, code, and corrections to make it better. As always, I owe “every one of you a big “thank you!” for all you have done and for all that you do. The Ruby community is still as vibrant, interesting, and (mostly) friendly as it ever was—that’s quite an achievement given the explosive growth we’ve enjoyed.

For the third (tenth anniversary) printing, Wayne E. Seguin was kind enough to check the section on the wonderful tool RVM, and Luis Lavena checked the section on installing under Windows, as well as the chapter on running Ruby on Windows. And I’d like to call Anthony Burns a hero for doing an amazing job of reading through the changes as I was writing them, but that would take away from the fact that he’s a true hero.[3]

Getting this book into production has also been a challenge. Kim Wimpsett is the world’s best copy editor—she’s the only copy editor I know who finds errors in code and fixes XML markup. Any remaining errors in this book are a result of my mistyping her suggested corrections. And, as we raced to get the book to the printer in time for RubyConf X, Janet Furlow patiently kept us all on track.

Finally, I’m still“deeply indebted to Yukihiro “Matz” Matsumoto, the creator of Ruby. Throughout this prolonged period of growth and change, he has remained helpful, cheery, and dedicated to polishing this gem of a language. The friendly and open spirit of the Ruby community is a direct reflection of the person at its center.

Thank you all. Domo arigato gozaimasu.

Dave Thomas

The Pragmatic Programmers

mailto:dave@pragprog.com

June 2013

摘录来自: Dave Thomas, with Chad Fowler, Andy Hunt. “Programming Ruby 1.9 & 2.0 (for Paul Simon)”。 

iBooks. https://itunes.apple.com/WebObjects/MZStore.woa/wa/viewBook?id=8157238F0256DE67CFC908B732219E64