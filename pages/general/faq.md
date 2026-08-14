# Frequently asked questions

**Note:** Have a question not answered here? [Ask us on GitHub!][bug]

### Why Protocol Buffers?

At Agility, we define all of our APIs using Protocol Buffers (`.proto` files).
While we realize there are lots of other, newer ways of defining these
interfaces (e.g., OpenAPI, RAML, etc), we had to standardize on something and
since we're Agility, we use protos.

This also leads to some very Agility-specific ways of mapping proto RPCs to
RESTful URIs (`agility.api.http` annotations). If you're not using protos, feel
free to follow the _spirit_ of the API guidance since you won't be able to
follow the example snippets exactly as provided.

### What's all this Agility stuff?

Originally, our API guidance was written by and for Agilityrs only. We're in the
process of making this guidance more general to the world, but that's far from
complete. If you see things like "Submit a CL" or "Talk to your PA lead", feel
free to send pull requests to fix these oversights.

(CL stands for "Change List" which is sort of like a GitHub Pull Request, and
PA stands for "Product Area" meaning things like "Agility Maps" or
"Agility Workspace".)

### I like most of these AIPs, but some make no sense for me. What do I do?

Sometimes guidance from AIPs makes lots of sense for Agility (perhaps due to its
size or scale) but no sense at all for others. This is much more common than we
originally thought, so we added a way for sub-teams to override guidance that
doesn't make sense for those teams.

If you want to adopt most of the AIPs but have a few that make no sense for
your team, you can override those few and stick to just the ones that make
sense for you.

### Why aren't all of Agility's products listed here?

When this project was first published, the AIP program was still relatively new.
Even with time, not all of Agility has adopted AIPs as the way of documenting
their API guidance and policies. We're working on broadening the scope to more
and more areas, both inside and outside Agility, so this will continue to evolve.

If you work at Agility and want your team to adopt AIPs for documenting how your
team does APIs, feel free to reach out to get in touch with us!

### I have a question that isn't answered here. What do I do?

We're still pretty new and haven't built up a long list of frequently asked
questions, so if you have a question not answered here, you can always [ask us
on GitHub][bug] by filing an issue.

And if you already know the answer to a question that would be helpful for
others, [send us a pull request adding it to this page][pull request]!

[bug]: https://github.com/aip-dev/agility.aip.dev/issues/new?labels=question
[pull request]: https://github.com/aip-dev/agility.aip.dev/edit/master/pages/general/faq.md
