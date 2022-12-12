# Creating a blogging pipeline from within Obsidian

I have wanted to start blogging for some time now but the friction of getting a domain, setting up a pipeline and *then* getting to the writing had been delaying it for me. It's one of the [asymmetric opportunities](https://twitter.com/naval/status/1054984950192181248) that feels the most accessible to me.

## Deciding on a flow

I started by trying to hash out what I wanted the flow to be. I wanted to answer these questions:

- Where would I write my articles
- Where would my server pick them up from
- Where would I end up seeing them

### Where would I write my articles
This was probably the easiest one, as the title suggests. I am very enthusiastic about Obsidian and it was primarily the trigger for me to start writing my thoughts. I wanted the richtext, markdown way of formatting to be preserved through the pipeline and look as appealing as it would on my desktop app.

### Where would my server pick them up from
This was also not that complicated to reason. I want my blog to be public and version controlled so I can just put it on Github. Github actions to regenerate the static site whenever there is a new commit.

### Where would I end up seeing them
I bought a domain today: `heyhx.xyz`
I have access to the DNS records so I will brainstorm where to host now. Maybe EC2 free tier will be enough. Or maybe I can just use some lambda functions to plumb. Anyway, I will set up a server with proper TLS certs and everything in the coming days. Will also document this process.