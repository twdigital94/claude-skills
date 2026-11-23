# TWdigital Claude skills

Free Claude skills for people running paid social and search ads, built and used day to day by [TWdigital](https://www.twdigital.co.nz/).

A skill is a set of instructions Claude loads when it's relevant, so it does a task your way every time instead of you re-explaining it.

## Skills

| Skill | What it does |
|---|---|
| [Meta ads build checklist](meta-ads-build-checklist/) | Turns scattered briefs, copy docs and creative files into one interactive tick-off checklist for building campaigns in Meta Ads Manager, in build order, with copy buttons, file names and budget maths done for you. |

More coming soon.

## How to install

### Claude.ai (web or desktop app)

1. Download the skill's ZIP from the [Releases](../../releases) page (or click **Code > Download ZIP** and zip the skill's folder yourself).
2. In Claude, go to **Settings > Capabilities > Skills**.
3. Click **Upload skill** and select the ZIP.

Then just ask, e.g. *"Build me a setup checklist for these Meta ads"* and attach your brief.

### Claude Code

Copy the skill folder into `~/.claude/skills/`:

```
git clone https://github.com/YOUR-USERNAME/twdigital-claude-skills.git
cp -r twdigital-claude-skills/meta-ads-build-checklist ~/.claude/skills/
```

## Make it yours

Each skill works out of the box, but it gets better when you add your own details. The checklist skill includes a client profile template for exactly that.

## About

Made by Tim Walker at [TWdigital](https://www.twdigital.co.nz/), Meta and Google Ads for New Zealand businesses. Questions or ideas? Get in touch through the website or on LinkedIn.

Free to use and adapt under the MIT licence.
