---
layout: post
title:      "Rails and Recipe Manager"
date:       2018-09-12 18:45:52 +0000
permalink:  rails_and_recipe_manager
---

While I'm glad to have worked through Sinatra first to understand all the things going on behind the scenes, I really appreciated how efficient Rails was and how much more quickly I could iterate through code development. Besides already having methods for things I was coding wonky workarounds for, learning the  syntax for methods like link_to saved so much time when creating new forms and view pages. The more Rails I learned, the DRYer my code became, which was nicely elegant, and every time I got to write something in Ruby instead of HTML felt like a small victory.

For my Rails project, I decided to build a simple recipe manager. The big lightbulb moment for me was that I could use an item model to function as a join table between recipes and ingredients with belongs_to and has_many through, which caused many elements of the project to neatly slide into place. This project was also my first real experience with OmniAuth, which initially seemed frighteningly technical (keys and secret keys? request.envs?!?!?!), but the Flatiron lesson and Avi's lecture basically reduced it to "how do we get a username out of the information GitHub is passing back?" which was not daunting at all.

This project didn't feel like it was as much of a "level up" as the Sinatra project was, but that's only because so much of the Rails curriculum wasn't new after Sinatra. Rails seems like it's a lot better for actually building functioning web apps in the real world, so unit was quite satisfying.

[GitHub Repo(https://github.com/kylekinnear/recipe-manager-rails)

[Demo](https://www.youtube.com/watch?v=nNfVXJvSFKo)
