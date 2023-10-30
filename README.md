# RC 2023 W1

## What Is This?
I'm currently taking part in the [Recurse Center](https://www.recurse.com/) W1 Batch. This is a place to put the things i'm currently working on and thinking about.

## What Am I Generally Working On?
Learning (how we can better create, collaborate on and consume information). I've previously explained what i'm trying to build as creating an open source learning ecosystem, similar to what Github has done for developers, but for learning more broadly. I'll be pushing changes as I make them (here)[https://www.nion.ai/] (assume everything uploaded for the next few months won't be persisted :) ).

## Specific Problems That I'm Thinking About/Working On
### Building an expressive block based editor optimised for learning
How do I build something which successfully meshes different media types/modes and is maximally flexible.

### Versioning a table in a relational database
Problem: How do I allow collaboration on content creation in a block based editor at scale?
Drill Down: If a table in a relational database contains records that have relations such the records form a cyclic graph, how do i store diffs in another table such that I can reconstruct previous states of that graph (both relationships and the content in each node)? How can I make this compatible with schema migrations?

### Creating & interpreting learning content with generative models
How can the effort barrier to creating and consuming content be lowered, and quality improved, for course creators & learners.

### Migrating a turborepo project to Clouflare Pages
Nion comes from the [t3 turbo stack](https://github.com/t3-oss/create-t3-turbo), it currently runs on Vercel and i'd love to move it to Cloudflare Pages. However, i'm struggling to successfully build a turborepo project on cloudflare.
