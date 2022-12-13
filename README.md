# GenServer Social Community tracker

A place to report issues, share community info, prioritize work, and see what's in progress. Please refer to the CODE_OF_CONDUCT.md and join the fun!

Contributions welcome.

> “Hello babies. Welcome to Earth. It's hot in the summer and cold in the winter. It's round and wet and crowded. On the outside, babies, you've got a hundred years here. There's only one rule that I know of, babies- God damn it, you've got to be kind.”
-- Kurt Vonnegut


## Community Guidelines

We are building a friendly and inviting online community geared towards Elixir/Erlang folks. This is non-exclusionary; if you're using different tech or no tech at all you are still welcome, we contain multitudes.

Disclaimers: We are (mostly) humans, humans are neither perfect nor consistent. We cannot expect systems built from humans to be perfect or consistent. What we should expect: patience, understanding and transparency. Please use the "report" button to call out things that are in violation of outlined policies, moderation decisions will err on the side of marginalized people.

We are all delightful and diverse individuals with a variety if interests. Off topic, and "shit posting" is okay provided that:
* if it's poking fun at something, it should be "punching up" (people / organizations in power) not "punching down" (marginalized groups)
* you are not impersonating brands / other officials / orgs / other things that will get our instance in legal trouble
* it's not purposefully unkind: don't make fun of other people's work, go make something yourself.
* use content tags where appropriate (is this a spoiler?, is it a wall of text? could this be borderline NSFW / traumatic?)

You will get one warning before an action is taken, moderation actions taken will be open and available to instance members.


### Guidelines

1. Sexually explicit or pointlessly violent media / gore is not allowed.
2. No racism, sexism, homophobia, transphobia, xenophobia, or casteism.
3. No incitement of violence or promotion of violent ideologies.
4. No harassment, dogpiling or doxxing of other users (if someone asks you to disengage, please do so).
5. No illegal content (this server is hosted in USA and will abide by US law)
6. No impersonating other people or creating multiple accounts to circumvent bans / mutes / other forms of moderation.
7. If you are a brand/company, please be mindful that there is no algorithm here: don't flood the feed with marketing. Please do share useful things that are generally helpful and engage with the community, but this isn't the place for repeatedly sharing your company's materials.
8. Right now we are not open to bots, you may follow and RT bots all you like, but signing one up to GenServer Social is not allowed for the time being.


## Longevity / Sustainability

This server is hosted on Digital Ocean. We have weekly application server backups, automated re-provisioning, and point in time snapshots for the database.  We will do our best to provide a 3 month warning in the case of an impending shutdown to give everyone the chance to move to a new home. We will also strive to communicate ahead of time any server updates / upgrades as they happen.

That said: this service is provided for free, without any warranty expressed or implied. If you are adverse to loss we encourage you backup your data via the settings UI. Messages are federated to other servers and are not encrypted. If you have private / business critical communications we recommend using another service. (eg Signal)


## The Blocklist

The block list will be made available to instance members who request it.

The current domain block list is the combination of blocks pulled and researched from similar tech focused instances and some additional domains found along the way.

Instances with feeds that have hate speech, apologia for hate speech, transphobic or homophobic content, illegal/copyrighted content, sexism, racism, fascist apologia, excessive/pointless violent content/gore do not fit within the goal of "building a friendly and inviting online community" and as such are blocked.

The block list is not static, we are happy to re-incorporate servers that are making a good faith effort to be a good neighbor.

If you are an admin and you believe your domain is blocked in error.  Please email us at `admin [at] genserver [dot] social`.

If you are a user at GenServer Social and have concerns about a domain, please message a moderator or email us at `admin [at] gensever [dot] social`.


## Current Todos:
- [ ] update to latest version of akkoma
- [x] write a better readme
- [ ] remote status dashboard
- [ ] consider elastic search
- [x] ~~publish current block list~~ Decided against this for now
- [x] define a process / considerations around how we're blocking instances
- [ ] investigate / install new frontend options
- [ ] clean up and commit terraform / deployment setup and push it to a repo
- [ ] automate packer image creation
- [ ] database failover node?
