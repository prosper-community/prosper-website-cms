# Prosper CMS

Prosper CMS is really just a [Ghost blog](https://ghost.org) that has a few static pages.

Ghost is a simple, powerful publishing platform that allows you to share your stories with the world. Ghost is maintained by a non-profit organisation called the **Ghost Foundation**, along with an amazing group of independent [contributors](https://github.com/TryGhost/Ghost/contributors).

- [Ghost.org](https://ghost.org)
- [Latest Release](https://ghost.org/developers/)
- [Support](http://support.ghost.org/)
- [Theme Docs](http://themes.ghost.org)
- [Contributing Guide](https://github.com/TryGhost/Ghost/blob/master/.github/CONTRIBUTING.md)
- [Feature Requests](http://ideas.ghost.org/)
- [Dev Blog](http://dev.ghost.org)

**NOTE: If you’re stuck, can’t get something working or need some help, please head on over and join Ghost's [Slack community](https://ghost.org/slack/) rather than opening an issue.**

# Developer Install (from git)

Install Node.js. (See [Supported Node.js versions](http://support.ghost.org/supported-node-versions/))

```bash
# Node v4.2+ LTS - recommended
# Node v0.10.x and v0.12.x - supported
#
# Choose wisely
```

Clone repo

```bash
git clone git@github.com:prosper-community/prosper-website-cms.git
cd ghost
```

Install grunt. No prizes here.

```bash
npm install -g grunt-cli
```

Install `node_modules`

```bash
npm install
```

Start your engines.

```bash
npm start

## running production? Add --production
```

More general [install docs](http://support.ghost.org/installation/) here in case you got stuck.

# Deploying

Deployment is managed by [Prosper](http://prosper.community) admins. If you need access to our servers, get in touch on our Slack team. You can request an invite here: [Volunteer Online](http://prosper.community/volunteer/#form).

# Staying Up to Date

When a new version of Ghost comes out, you'll want to look over these [upgrade instructions](http://support.ghost.org/how-to-upgrade/) for what to do next.

# Copyright
Copyright (c) 2015-2016 Prosper Community
