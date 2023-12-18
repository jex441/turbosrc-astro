---
title: 'Announcing Turbosrc: empowering contributors'
description: 'David Szigeti'
pubDate: 'October 26, 2022'
heroImage: '/blog-placeholder-4.jpg'
subText: 'In a previous blog post, we outlined a vision for rewarding contributors, self-sustaining open source projects, and improving security.'
---
![Turbosrc logo](/logoviolet.png)

In a previous [blog post](/blog/exploitation-of-contributors/), we outlined a vision for rewarding contributors, self-sustaining open source projects, and improving security.

## Alpha Launch
We are pleased to announce the alpha release of [Turbosrc](https://www.turbosrc.org) (pronounced “turbo source”) – free and open source software that empowers contributors as stakeholders. Here is the source code on [Github](https://github.com/turbo-src). You can launch your own private instances if you choose. We still have a lot of work to polish for beta launch.

The idea is simple. A maintainer gets a supply of 1 million VotePower for their project they put on Turbosrc. They can distribute VotePower to contributors, supporters and sponsors as they see fit.

- VotePower holders can transfer any amount of their VotePower to others
- You weigh in on pull requests with VotePower - accept or reject
- It can be used seamlessly on your current Github projects (more code hosts to come)
- Turbosrc is not affiliated with Github - Turbosrc has a web extension
- Turbosrc has unique IDs for pull requests under the hood (cross-platform)


![Login with Github](/loginwithgithub.png)

*Login with Github*

![Vote directly on pull requests](/votebuttons.png)

*Vote directly on pull requests*

We have made a cloud hosted version available to alpha users. It comes with a web extension that works for Github projects - incentivizing developers, democratizing code development, and lowering the day-to-day burden of maintainers in ways once unimagined. More code hosts other than Github are to come, including a stand-alone web and cli app.

Alpha access is available to lobste.rs users here on [turbosrc.org](https://turbosrc.org/#alpha).

## Democratize your code (no rush)
Maintainers can keep a majority of VotePower, or not. It’s up to them. Maintainers may choose to transfer VotePower democratically. Or they may retain majority VotePower, especially useful for younger projects that need to pivot or break things a lot.

Maintainers and other large holders of VotePower can choose to relinquish more VotePower over time. They can become more democratic as the project matures or hand over the reins completely to another core contributor group when they want to exit the project due to life or career changes. Or they could handover all their VotePower to their AI personality forever (just joking, please don’t).

There is no formula to tell you how to distribute VotePower initially as a maintainer. Just be mindful that others can transfer VotePower once you give it to them.

## Social-driven automation and bots
Turbosrc will help projects that need to achieve a high velocity. Stakeholding contributors can vote on pull requests around the clock in different time-zones, eliminating any bottlenecks if a maintainer is asleep or wants to go on vacation. The maintainers' trusted group of contributors reflected by their respective VotePower can lighten the load. And the maintainer doesn’t risk betrayal or carelessness on part of those with access control making code merges on their behalf.

And in a world racing towards increased AI in code development, Turbosrc offers a safe path forward. Giving a bot access control to merge code is risky. But with VotePower, stakeholders can launch bots to vote alongside others, such as a bot that flags insecure dependencies. That way there are built-in checks-and-balances, natural buffers, and sum-greater-than-parts effect. This is better than relying on a single AI system. All of this is possible as there will be a public api for Turbosrc users to automate against.

## Sponsorship and funding opportunities
You can also give sponsors (who’d appreciate it) of your project some VotePower. They’ll want to help out more if they’re directly engaged or have something of value. VotePower actually does something. This is better than the status quo: generally sponsorships (Open Collective to Github sponsors) are non-tax deductible expense in the United States. Tubosrc can compliment any sponsorship gesture. A win-win.

Most of the benefits of Turbosrc, we believe, can be achieved without Web3. One day, however, for maintainers that want that, sponsorship costs could be capitalized costs instead. Something that retains value via VotePower-Web3.

Turbosrc is a hosted service out-of-the-box. It’s not blockchain. However, others can choose to fork Turbosrc and ‘swap out’ VotePower for Web3 VotePower implementation. Turbosrc is modular by design and it’s fully open-source, so anyone is free to do this - just like anyone can use Linux for for whatever they want. Again, Turbosrc stands on its own without Web3.

## Contributing to Turbosrc itself
We have a lot of room for improvement. We haven’t tightened up the code base yet. We’re a small team that bootstrapped this. We don’t fully-utilize the power of our graphQL api, which ties together all the Turbosrc subservices. We need to work towards ci/cd. There are lots of opportunities for those interested at all skill levels.


