---
date: '2026-08-18T09:03:45+01:00'
draft: false 
title: 'There Is Nothing Like Owning Your Place on the Internet'
tags: ["project", "leaning", "Git", "Vim", "Hugo"]
cover:
    image: images/mountain-clouds-cover.png
    alt: "Illustration of a mountain peak rising into the clouds"
---
There's no place like home. Specifically, buying your domain and owning your website: the place where you're in charge of building and maintaining what you write and share with your guests.

This is a part of "learning in public": the practice of sharing what you learn *while* doing it. Showing not only the "finished product", but the iterations, the setbacks, and the solutions you've found and applied.

I first read about this practice a few years ago from swyx (Shawn Wang) [^1], former financial analyst first turned developer and now an AI engineer. Last year I came across it again, while reading the book "Share Your Work", by Austin Kleon, a recommendation by Mischa van den Burg. After that, I decided to do it myself.

This is the first project I created after deciding to change careers from OR Nurse into the technology field, specifically to the DevOps area. Building it on my own domain forced me to take full responsibility for the infrastructure from the start. It was a deep dive into the fundamentals, but it helped me develop the troubleshooting mindset essential for this new career. It's a work in progress and will evolve as I advance in the learning roadmap.

## The Why and the How

The main goal of this website is to be the place where I document the learning process and the subjects I'm studying as I build a solid technical foundation. While I could have opted for a ready-to-use solution, my intention was also to learn how to use essential tools that are part of a DevOps professional's routine.

In that sense, I chose Hugo as a static site generator to manage the whole workflow from the command line interface (CLI). While I initially built the site in VS Code to get a head start, my goal was to move to Vim once the foundation was set. Since then, I've been using Vim exclusively for editing the Markdown files. 

The project is version controlled in a public GitHub repository, with deployments automated through continuous integration with the hosting provider.

The workflow generated provides a small-scale sample of some of the tools and practices I'll be developing in the months to come.

## Adopting the Conventional Commits Standard

When I started this project, my previous knowledge of the tools I ended up learning about was minimal. I had only used Git in a superficial way during a previous experiment.

When time came for version control, I used informal Git commit messages to log changes in the repository. At the time, I learned the essentials to advance with the development.

Recently, I had the opportunity to adopt the Conventional Commits standard for this project. This is the standard used by large development teams and many open-source projects that allows for clarity, consistency, and good communication of the project's history. It also facilitates collaboration between contributors.

Instead of changing the whole commit history of the project, I decided to preserve it as is and follow the new standard from the adoption date forth. It's a choice to reflect its evolution and to document what I've recently learned. This change was documented in the project's README.md file.

## Final Thoughts

Last year, I wrote a blog post reflecting on the learning journey ahead of me: [Climbing Mountains Into the Clouds](https://monicahbettencourt.com/posts/climbing-mountains-into-the-clouds). It reminded me of a beginner mountain climber looking at a mountain ridge and realizing the amount of effort ahead. 

It still does, and in a good way. That post featured a photo of Mount Pico, which inspired this analogy. This time around, I created the mountain image you can see here myself. It serves as a reminder that the foundational knowledge I'm building is essential for the next steps up in the learning ascent.

I enjoy what I'm studying and every day I discover how to do something new or why it's built in a certain way. The pieces are fitting into place one by one, and the discovery is delightful.

[^1]: Link to swyx's blog post "Learn In Public" - https://swyx.io/learn-in-public
