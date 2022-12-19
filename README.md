## tl;dr:

Easily configure and deploy an app for your Nouns-based DAO. Beautifully designed and hand crafted. Built with accessibility and wonderful developer and user experience in mind. 

The artwork used throughout our prototype is by [Adam Ho](https://www.adamho.com/).

https://user-images.githubusercontent.com/11803153/208446645-1522b05b-e07c-4ec6-b323-d92805ba54b3.mp4

## Proposal details

We’ve been interested in working within the nouns ecosystem for a while, and thought this would be a good opportunity to build something for the community. We’re excited about the concept of easy-to-deploy and customizable apps for Nouns-based DAOs. We’ve worked on the design and overall architecture of our submission, and should the proposal be accepted, we will build out the full product based on everything listed here.

## Design & features


https://user-images.githubusercontent.com/11803153/208448267-6056eb9e-59dd-4d42-9c07-508f73a3ef20.mp4


### Auctions

- View auctions
- Bid on auctions
- Show bid history
- Keyboard navigation

### About

https://user-images.githubusercontent.com/11803153/208448391-ec89d83c-3fc5-4a48-845e-d5c0fa915264.mp4

Section on the homepage about the DAO with the following:

- DAO metadata such as avatar, name, website, social links
- Treasury stats

### Proposals

<img width="1696" alt="004_nouns_proposals_list" src="https://user-images.githubusercontent.com/11803153/208448925-7a7f1963-4451-4cf8-a689-729cf6a4ee08.png">

We’ve designed the overview of proposals to be simple, but with a higher density of information, showing:

- Proposal number
- Proposal title
- Proposer (ENS or address), including avatar
- Number of votes
- Simple stacked bar chart that shows the proportion of votes in favor, against, and abstaining
- The status of the proposal

#### A proposal

https://user-images.githubusercontent.com/11803153/208448964-b304f7f1-7127-4ce8-9725-556da6b1d189.mp4

We’ve designed the proposal page to show the status of a proposal at a glance, yet enable a high degree of expression in its description.

- Title shows the status, (end) date, and the breakdown of votes
- Ability to see who voted in favor/against/abstained
- Two-column description, with markdown on the left and a right column that shows the proposer, links, and stats.
- Proposed transactions at the bottom of the page
- Sticky buttons for voting

### Technial architecture

### Tooling

- [Remix](https://remix.run/)
- [React Query](https://tanstack.com/query/v4/)
- [wagmi](https://wagmi.sh/)
- [rainbowkit](https://www.rainbowkit.com/)
- [Radix components](https://www.radix-ui.com/)
- [Tailwind](https://tailwindcss.com/)

### Customizable

https://user-images.githubusercontent.com/11803153/208449107-83ae4495-01b6-415c-9e57-afa924d7f66f.mp4

We’ve designed everything to be easily customizable based on a default theme or a theme you provide. All the core functionality of the app is synced from the DAO smart contract, with easy to update components and markdown support. To get started, you only need to set some environmental variables and deploy.

### Extensible

Each component will be well documented with comments and any team that has familiarity with Remix and React should be able to modify and add features as they need. If folks are happy with our project, we’d love to pursue follow up proposals to add new features :)

### Easy to deploy

Documentation will include examples on how to (ideally) one-click deploy to the following providers: Vercel, [Fly.io](http://fly.io/), Render, Netlify, and Cloudflare Pages.

## The team

We’re [Jenna](https://twitter.com/jjenzz)], [Thomas](https://twitter.com/aulneau_), [Jasper](https://twitter.com/jasperjansz) and Graeme, aka [Fungible Systems](https://fungible.systems) — a design and engineering studio with a focus in web3 and crypto. Since starting our studio earlier this year, we’ve had the pleasure to work with some of the industry’s biggest names and most promising startups. We’ve been interested in participating in the Nouns ecosystem for some time, and thought this would be a wonderful entrance into the space.
