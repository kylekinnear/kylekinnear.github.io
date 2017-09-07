---
layout: post
title:  "My CLI Gem Project"
date:   2017-09-06 16:55:05 -0400
---

While moving through the OO Ruby part of the Learn.co curriculum, I noticed scraping was an upcoming topic. It was a subject I could really look forward to because of the utility in learning how to grab data off the internet. Sure enough, I enjoyed the lesson, was glad to get more practice writing CSS selectors, and promptly set to work writing a scraper for my personal use.

I really enjoy reading and keep a spreadsheet of upcoming books that I'm interested in because someone's recommended them to me, the blurb seems interesting, or I've read and enjoyed books by the author before. The problem with this is that book release dates change (or I take note of a book I want to read before it has a firm release date). Checking release dates entry by entry by searching author websites, Amazon, and Goodreads is pretty tedious, but expecting a book release only to find out it's been moved back three months is a huge disappointment. So I wrote my first scraper to quickly take a search term and grab info on the top Goodreads result for that term to expedite keeping release info up-to-date. My scraper did everything I wanted it to do - scraping was great!

When I read the description for the CLI Gem project, I was pretty excited to do more scraping. I immediately thought of another take on my book info scraper. My current program was great for learning more about books I already knew enough about to generate a search term (author, title, and/or series name and number, for example), but wasn't any good at all for discovering new books. I knew that Amazon has daily Kindle deals, so that seemed like a great place to start.

Unfortunately, Amazon wasn't as enthused as me about my great idea and blocked my program from scraping their site. I was a little disappointed to learn that scraping isn't an all powerful tool to grab all the information on the internet. That sent me back to the drawing board (and Google searches to find sites with their own listings of ebook deals). That brought me to the [EbookDeals subreddit](https://www.reddit.com/r/ebookdeals/).

After a couple days observing common formats of post names (and writing CSS selectors to grab authors, titles, and price info from them) and figuring out the best ways to use that information to create the most relevant Goodreads search term (I'm interested in Maya Angelou's *I Know Why The Caged Bird Sings*, not the SparkNotes for the book), I had a working program. I turned the program into a gem and unleashed it on the unsuspecting world (I uploaded it to RubyGems). I've been running the gem every day and gone nearly a week without it breaking (with a sigh of relief every time). I'll probably revisit it to add other sources so I can discover more books (bestseller lists, maybe?), but for now it's done - and I really enjoyed the process of getting here.

[Github Repo](https://github.com/kylekinnear/EbookDealInfo)

[RubyGems](https://rubygems.org/gems/ebookdealinfo)

[Ebook Deal Info Demonstration Video](https://www.youtube.com/watch?v=UEzGCP_sPdQ)
