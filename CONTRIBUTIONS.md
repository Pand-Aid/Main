# Contributing to Pand-Aid 

## Welcome 
We are thrilled to see you here! Thank you for contributing to Pand-Aid. We are an inclusive community that is commited creating a welcoming development environment for all who join us.  

The following is a set of guidelines to help you navigate the contribution process. Please check back often in these early days as these guidelines are likely to be updated to some extent as we get more code up and solidify more of our processes. 

Now... Let's get coding! 

## Joining a Team 

We suggest that you join a team (Frontend, Backend, API, Database, Security, React, etc.) and become connected with our community before you start issuing pull requests. 

Currently we are in need of more Frontend developers.

We are doing the majority of our organizing via slack at the moment, but we are adding other group project tools daily. You can join our slack channel [here](https://join.slack.com/t/pand-aid/shared_invite/zt-crh7rsu8-Qbs3c44qRGHkaPtJH74PEA). 

Once you are there please introduce yourself on the _#intros_ channel and we will get you settled into a team. Feel free to let us know your pronouns if you are comfortable with it, but if it is an area you are still exploring or finding your footing on, we will not pressure you. From there we can add you into our organization teams on github. 

Finally, don't forget to read our [code of conduct](). It is vitally important to us that we treat everyone on our team with respect regardless of age, religion, political affiliation, sex, gender, race, orientation, disability, or skill level. 

## Tool Enhancement Suggestions 

## Pull Request Process 

The process here has a few goals, and will be updated as our workflow develops further over time.(For example, we are working on templates for different types of pull requests). 

1. Maintaining the quality of Pand-Aid 
2. Making sure our community has a straightforward process in place for contributing
3. Addressing issues vital for the success of Pand-Aid and enhancing the experience of its users. 
4. Enabling a sustainable system for Pand-Aid's maintainers to review and approve contributions. 

---
### Starting a new pull request

- Contact a project Lead or Brianna (NinjaBee) to discuss the update you would like to make and why. 
- Clone and Fork to your own github before making a branch. 
- Test your code. 
- When submitting a merge to a branch or master on Pand-Aid please follow the following structure: 

>    git commit -m "One line of descriptive commit message  followed by a blank line. 
>    
>    A paragraph explaining in detail what update has been made and what it's intended use/improvement is."

- Once you have requested a merge, update the history.md file with a brief explaination of your work (can be the same as your commit message), issue number if applicable, first 7 numbers of the SHA if applicable, and the date-time (this can be an estimate). 
- Make sure your code is well commented or it may not be approved.

## How do I submit an enhancement solution? 

Official enhancement suggestion are tracked as GitHub issues. However you can also approach one of the leads or Brianna for a quick brainstorming session and may have the fastest turn-around. Once you know that you would like to make your idea into an official request you need to determine which repository your enhancement is related to, submit an issue in that repository and provide the following information: 

- **A number in sequence with any other issues**
- **A clear descriptive title** 
- **Provide a description of the enhancement with steps if applicable.** 
- **Explain what behavior you saw** vs **what behavior you expected to see and why.** (if applicable) 
- **Explain why this enhancement would be useful** 
- **Tell us what browser you are/were using when you noticed the behavior.** (if applicable)
-**Provide any additional information you believe may be relavent or useful. ** 

# Style Guides 

When in doubt be extra clear, extra clean, and keep things simple and follow PEP8.

1. Your code should be written as close to plain English as possible. No single or double letter variables like `xd = 1 + 2`.  
2. Variables, functions, and classes should all be named with thought towards making it obvious what it is for/what it is related to. If it needs multiple words to do this, use multiple words. 
3. Comment your code. You do not need to comment every line, but your code should both be self commenting through good naming practices, and have comments explainig what is being achieved in larger blocks.
4. Lists should be plural. 
5. Modular is better than 300 lines. If your code is getting chunky, consider how you can break it down into further parts. 
6. Import one module per import statement
    import os
    import sys

Not: 
    import os, sys

7. Seperate imports into groups with a line of whitespace: standard library; Django or other framework; third-party; and local imports: 
    import os
    import sys

    from django.conf import settings

    import pyquery

    from thisapp import models, views
8. Imports on top, `from` imports below:
    import this
    import that
    import another
    from something import chaos
    from music import sound
    from quails import eggs

It's a lot easier to read than:

    from music import sound
    import this
    import quails import eggs
    import another
    import that
    from something import chaos


#That's it folks! 

You did it! You made it to the end... now... where's the coffee and code? Let's go help some people! 

    
