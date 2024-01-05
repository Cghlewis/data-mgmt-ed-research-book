---
title: "Data Management in Large-Scale Education Research"
author: "Crystal Lewis"
date: "2024-01-05"
site: bookdown::bookdown_site
documentclass: book
bibliography: book.bib
# url: your book url like https://bookdown.org/yihui/bookdown
# cover-image: path to the social sharing image like images/cover.jpg
cover-image: book_featured.PNG
description: |
  This is the in-progress version of *Data Management in Large-Scale Education Research*. 
biblio-style: apalike
link-citations: yes
---

# Welcome {-}

<img src="book_featured.PNG" class="cover" width="250" height="328"/>This is the in-progress version of *Data Management in Large-Scale Education Research*. When completed, this book will be published by [CRC Press](https://www.routledge.com/Data-Management-in-Large-Scale-Education-Research/Lewis/p/book/9781032622798). This free, online version is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

## Endorsements {-}

> Imagine having a seasoned researcher's best advice at your fingertips---this is precisely what this book offers. It's a well-crafted blend of practical know-how and scholarly wisdom, perfect for anyone about to or currently managing research data. With clarity and a touch of scholarly flair, Crystal Lewis transforms complex concepts into clear, actionable steps. It's packed with real-world examples, straightforward templates, and checklists that take the guesswork out of data management. Whether you're a seasoned investigator, a data manager, or a student stepping into the world of research, this book will undoubtedly become a staple in your professional toolkit, enhancing the quality and impact of your work. This book is a resource that speaks your language, understands your challenges, and respects the depth of your work. In summary, this book is not just a guide; it's a mentor in print form.
>
> **Joscelin Rocha-Hidalgo**, Pennsylvania State University

> *Data Management in Large-Scale Education Research* is a game changer for education researchers wanting to improve their research practices. The book seamlessly blends theory and practice, offering a pragmatic guide for ethically and systematically managing and sharing data.
>
> **Crystal Steltenpohl**, Center for Open Science

> This book is a direct answer to the critical need for practical and accessible resources for education researchers who are managing primary data collection. Crystal Lewis introduces robust methods for the collection and management of data within the broader research context. Readers will acquire knowledge and confidence in leading large-scale studies, as well as skills and strategies they can implement in their work immediately. This book should be on the shelves of all graduate students, project managers, data managers, and PIs conducting research in education!
>
> **Leigh McLean**, Center for Research on Educational and Social Policy, University of Delaware

> Education researchers: do not skip this book! Crystal Lewis gives you the tools you need to manage your data better in order to make your project run smoothly.
>
> **Kristin Briney**, Biology Librarian, California Institute of Technology, and author of [Data Management for Researchers: Organize, Maintain and Share Your Data for Research Success](https://pelagicpublishing.com/products/data-management-for-researchers-briney)

> An outstanding guide for those learning how to manage large-scale data in the social sciences. The book embraces the tenets of open science, highlighting the importance of reproducible science.
>
> **Lexi Swanz**, Vanderbilt University

> Crystal Lewis has translated years of experience in applied research into a practical and indispensable guide to all aspects of data management across the educational research cycle. This book provides everything you need to perfect your data management practices and engage in research that is consistent with open science principles and the ever evolving demands of grant funding agencies.
>
> **Dan Cohen**, SRI International

> This book is a treasure for those in field of Education and beyond. Many practicing statisticians and industry data scientists have never endured the process of collecting their own data, and statistical education largely assumes away such complexities, taking complete and correct data as a given. Lewis' incredibly clear and readable book can be a revelation to data analysts on the complexity, nuances, and subjectivity that goes into data collection. This framework will undoubtedly help many consider how to handle bias and complexity in their own analysis and better manage their derivative data products with the level of care that Lewis provides to her readers.
>
> **Emily Riederer**, Capital One, and author of [R Markdown Cookbook](https://www.routledge.com/R-Markdown-Cookbook/Xie-Dervieux-Riederer/p/book/9780367563837)

> *Data Management in Large-Scale Education Research* covers all angles of data management, spanning the entire research life cycle. This book helps readers critically think through how to set up processes to ensure you have accurate data in the end. It clearly explains data management topics that are commonly confusing, unknown, or simply forgotten, as well as addresses new requirements in education research.  Checklists and workflows are also provided to help readers complete tasks in an organized fashion. This book is a great resource that will save your team time in researching how to manage data and will get your study started on the right foot, with confidence.
>
> **Tara Reynolds**, Data Manager, Florida Center for Reading Research

## Book key features {-}

This book includes the following key features:

- Provides a holistic approach to the research life cycle, showing how project management and data management processes work in parallel and collaboratively
- Can be read in its entirety, as well as referenced as needed throughout the life cycle
- Includes relatable examples specific to education research
- Includes a discussion on how to organize and document data in preparation for data sharing requirements
- Contains links to example documents as well as templates to help readers implement practices

## About the author {-}

I am a freelance research data management consultant and trainer ([cghlewis.com](https://cghlewis.com/)). I have a Master’s degree in Public Policy from the University of Minnesota, Twin Cities. My experience spans the research life cycle including collecting, curating, sharing, and analyzing data, particularly for studies funded by federal grants. I am happiest working at the intersection of education research and data management planning, helping researchers build and implement organized processes that lead to more secure, reliable, and usable data. I am a co-organizer for two community groups---R-Ladies St. Louis, an organization focused on promoting gender diversity in the R community, as well as the POWER (providing women opportunities in education research) data management hub, where I facilitate peer data management support in the education research community. 

## Acknowledgements {-}

This book is a compilation of lessons I have learned in my personal experiences as a data manager, knowledge collected from existing books and papers (many written by librarians or those involved in the open science movement), as well as advice and stories collected through interviews with other researchers who work with data. I want to be clear that I did not formally study research data management, unlike research data librarians who are experts in this content. Much of this book will be based on lessons learned from firsthand experience, and this book is my attempt to hopefully save others from making the same mistakes I have personally made or seen others make. I cannot emphasize enough that if you work for a university and you have the opportunity to consult with a librarian for your project, you absolutely should!

With that said, there is a long list of people I would like to acknowledge for their contributions to this book and for supporting me in this process.

There were many people who graciously allowed me to interview them about their current data management practices. They are Mary McCraken, Ryan Estrellado, Kim Manturuk, Beth Chance, Jessica Logan, Rebecca Schmidt, Sara Hart, and Kerry Shea. These interviews were integral to supplementing my personal knowledge with the broader experience of others in the field. They also affirmed that yes, data management is hard, especially in the context of some of the complicated study designs we work with in education research, and that everyone who works in this field wishes that better training, support systems, and standards existed. Thank you to everyone who gave me an hour of their time to share their experiences and knowledge! I also have to give a special thank you to Jessica Logan for being the first person I met who appreciates all things data management as much as I do, and since having our interview, has provided invaluable support while working on this book.

A big thank you to David Grubbs and Curtis Hill at CRC Press for supporting me through the publishing process. Also, thank you to everyone who took the time to read and provide feedback on chapters of this book. This includes Meghan Harris, Lexi Swanz, Ally Hanson, Rohan Alexander, Peter Higgins, Emily Riederer, Priyanka Gagneja, Jennifer Huck, Danielle Pico, Kristin Briney, Hope Lancaster, Gizem Solmaz-Ratzlaff, Crystal Steltenpohl, Leigh McLean, Jessica Logan, Chris Schatschneider, Tara Reynolds, Kerry Shea, Joscelin Rocha-Hidalgo, John Muschelli, and Sara Hart. Your revisions and insight helped make this a more cohesive and useful book! 

A special thank you to Keith Herman as well. Many years ago he suggested I write a book titled Data Management in Large-Scale Education Research, which seemed unimaginable to me to me at the time. Thank you to Keith for envisioning this book long before I ever could.

Much appreciation to Wendy Reinke as well. Joining a project where she had already created documentation and tracking systems was my first glimpse into building tools that help you manage data, and my love of research data management grew out of this experience.

I want to say thank you to the POWER Issues in Data Management in Education Research Hub. Regularly meeting with this group of data managers, researchers, students, and professors over the last two years has been an amazing source of both support and learning and has greatly increased my understanding of data management.

Last, thank you to Josh for fully supporting me in the decision to write this book and to Fox for being the reason I remember to step away from my computer from time to time and have fun.
