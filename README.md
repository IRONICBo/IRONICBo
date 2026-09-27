# Asklv

I build local, evidence-first browser agents.

[![Jev Social — Jev × socai][jev-banner]][jev-social]

## Jev Social

One research goal → Jev chooses a bounded next step → `socai CLI` runs it in
your Chrome → captured posts become a source-linked report.

[Source][jev-social] · [Live overview][jev-site] ·
[Recorded 64-second Instagram run][instagram-evidence] ·
[TikTok video evidence][tiktok-evidence]

Try v0.1.10 with Node 20+, Chrome already signed in, and an OpenRouter key:

```sh
npx github:socai-io/jev-social#v0.1.10 onboard
npx github:socai-io/jev-social#v0.1.10
```

Jev Social supports read-only Instagram, TikTok, and LinkedIn research. It
keeps partial and blocked runs visible instead of turning missing evidence into
a success claim.

## socai

[`socai`][socai-repo] is the local browser runtime behind Jev Social. It
searches and reads social content in the user's Chrome and returns structured
evidence to the caller.

[Website][socai-site] · [Source][socai-repo] · [Discord][discord]

[discord]: https://discord.gg/CpQdA7bwt8
[instagram-evidence]: https://github.com/socai-io/jev-social/blob/main/docs/example-report.md
[jev-banner]: https://raw.githubusercontent.com/socai-io/jev-social/main/docs/banner.png
[jev-site]: https://socai-io.github.io/jev-social/
[jev-social]: https://github.com/socai-io/jev-social
[socai-repo]: https://github.com/socai-io/socai
[socai-site]: https://socai.io/
[tiktok-evidence]: https://github.com/socai-io/jev-social/blob/main/docs/tiktok-evidence.md
