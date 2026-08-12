## Peter Fasae

Software engineer in London, working mostly on the backend — APIs, data and tests.

I'm currently building **Clarity**, a note-taking system for people with ADHD. Most of the
engineering went into one question that isn't really about notes: *when is a note allowed to
leave the system?* A note only reaches a third-party AI service once someone has explicitly
turned that on, and there's a test that fails if a single request escapes while it's off — it
watches the network rather than inspecting the code, so it catches paths I didn't think of.

121 tests. Serverless on AWS: Lambda, API Gateway, DynamoDB and Cognito. Not deployed yet.

**[Read the case study →](https://peterfasae.github.io/clarity.html)**

### Why there isn't much here

Most of what I've built isn't public. Clarity is private while it's unfinished, and my
commercial work belongs to the companies I did it for. The write-ups on my site are the
evidence in the meantime, and if you'd like to look at real code I'm happy to walk you
through it.

### Elsewhere

- **Portfolio** — [peterfasae.github.io](https://peterfasae.github.io/)
- **LinkedIn** — [peter-fasae](https://www.linkedin.com/in/peter-fasae-5a7482b8/)
- **Email** — pfasae@gmail.com

<sub>Open to backend and full-stack roles in London, or remote.</sub>
