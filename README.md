[Firefox Relay](https://relay.firefox.com) provides emails masks for
[Firefox Accounts](accounts.firefox.com/) users with a domain of `mozmail.com`,
or (for paying users) a subdomain of `mozmail.com`. Some services deny
registration or avoid emailing
[disposable email addresses](https://en.wikipedia.org/wiki/Disposable_email_address).
We try to keep `mozmail.com` off these deny lists, so that our users can use
their email more places.

# Disposable domain lists

These repositories maintain lists of disposable email addresses.

|Repository|Has mozmail.com?|Age|Note|
|:---------|:---------------|:--|:---|
|[7c/fakefilter](https://github.com/7c/fakefilter)|No|Active|Looks for temp and fake emails in registrations, backend for [fakefilter.net](https://fakefilter.net/static/docs/restful/)|
|[FGRibreau/mailchecker](https://github.com/fgribreau/mailchecker)|No|Active|Multi-language email validator and temp email detector|
|[GeroldSetz/Mailinator-Domains](https://github.com/GeroldSetz/Mailinator-Domains)|No|Jun 2021|Domains in sha1 format|
|[GeroldSetz/emailondeck.com-domains](https://github.com/GeroldSetz/emailondeck.com-domains)|No|Jun 2021|Follows [www.block-disposable-email.com](https://www.block-disposable-email.com/cms/)|
|[MattKetmo/EmailChecker](https://github.com/MattKetmo/EmailChecker)|No|Feb 2023|PHP disposable email detector|
|[adamloving/temporary-email-address-domains](https://gist.github.com/adamloving/4401361) (Gist)|No|Jul 2019|Comments advertise other services|
|[amieiro/disposable-email-domains](https://github.com/amieiro/disposable-email-domains)|In [allow domains](https://github.com/amieiro/disposable-email-domains/blob/61715794c3b8a54dfe54716f57b2676024cbd1ae/allowDomains.txt#L338)|Active|Combines lists from other sources|
|[auth0-signals/disposable-email-domains](https://github.com/auth0-signals/disposable-email-domains)|No|Aug 2020|Submissions to defunct site apility.io|
|[codeAshu/fakemails.txt](https://gist.github.com/codeAshu/ebade8f300809a4079220f771265b0c4) (Gist)|No|July 2018|List of domains, comments suggest changes|
|[daisy1754/jp-disposable-emails](https://github.com/daisy1754/jp-disposable-emails/)|No|Jun 2021|List of domains from other sources|
|[disposable-email-domains/disposable-email-domains](https://github.com/disposable-email-domains/disposable-email-domains)|In [allow list](https://github.com/disposable-email-domains/disposable-email-domains/blob/3ff014e9a26f29b9e60ac2b3633747f4de03cf83/allowlist.conf#L119)|Dec 2022|block and allow list|
|[disposable-email-domains/python-disposable-email-domains](https://github.com/disposable-email-domains/python-disposable-email-domains)|In [allow list](https://github.com/disposable-email-domains/python-disposable-email-domains/blob/98537f0a155348052f33d93fb24d0b2633ddfb7a/disposable_email_domains/__init__.py#L120)|Active|Above lists as Python sets|
|[disposable/disposable-email-domains](https://github.com/disposable/disposable-email-domains)|No|Active|Text and JSON lists of domains|
|[disposable/disposable](https://github.com/disposable/disposable)|On [greylist](https://github.com/disposable/disposable/blob/6499a0d1511bf5f3578dcfd57c552d5e6eea4819/greylist.txt#L23) starting Nov. 2023|Active|Tools for working with domain lists, with list of external sources|
|[disposable/static-disposable-lists](https://github.com/disposable/static-disposable-lists/)|No|Apr 2022|Email domains that can't be dynamically updated|
|[ivolo/disposable-email-domains](https://github.com/ivolo/disposable-email-domains)|No|Sep 2022|Source for [Kickbox.com API](https://open.kickbox.com/v1/disposable/mailinator.com)|
|[jamesonev/disposableEmailDomains.txt](https://gist.github.com/jamesonev/7e188c35fd5ca754c970e3a1caf045ef/) (Gist)|No|July 2020|List from defunct block-temporary-email.com|
|[jespernissen/disposable-maildomain-list](https://github.com/jespernissen/disposable-maildomain-list)|No|Aug 2021|List of domains|
|[kslr/disposable-email-domains](https://github.com/kslr/disposable-email-domains)|No|Active|Text and JSON lists of domains, updated from upstream daily|
|[maximeg/email_inquire](https://github.com/maximeg/email_inquire)|No|Jan 2020|Ruby library to validate and fix emails, detect disposable emails|
|[micke/valid_email2](https://github.com/micke/valid_email2)|No|Active|Ruby gem to validate emails, detect disposable emails|
|[mits87/disposable-email-provider-domains](https://github.com/mits87/disposable-email-provider-domains)|No (repo),<br>**Yes (current release 1.0.9)**|Active|NodeJS wrapper|
|[smudge/freemail](https://github.com/smudge/freemail)|No|Oct 2022|Ruby port of willwhite's freemail|
|[stopforumspam/disposable_email_domains](https://github.com/stopforumspam/disposable_email_domains/)|No|Apr 2023|List of domains. May be old version of toxic domains download on https://www.stopforumspam.com/downloads|
|[wesbos/burner-email-providers](https://github.com/wesbos/burner-email-providers)|No|Active|List of emails, links to Firefox Relay|
|[willwhite/freemail](https://github.com/willwhite/freemail)|No|July 2020|List and Node.js module|

# Services

These provide plugins and an API for checking an email address.

|Main Site|API|mozmail.com result|Copyright|Note|
|:--------|:--|:-----------------|:--------|:---|
|[block-disposable-email.com](https://www.block-disposable-email.com/cms/)|[api.block-disposable-email.com/easyapi](https://www.block-disposable-email.com/cms/help-and-usage/easy-api/) (free registration), [Try it](https://www.block-disposable-email.com/cms/try/) (with CAPTCHA)|**`fake-email-address`, block it**|2021|Provides API with [free registration](https://www.block-disposable-email.com/cms/register/).|
|[block-temporary-email.com](https://block-temporary-email.com)|Yes|Not temporary|*none*|Freemium service|
|[block-trashmail.space](https://www.block-trashmail.space/)|[Yes](https://www.block-trashmail.space/api/mozmail.com)|`0` (not on blacklist)|*none*|Free service, no rate-limit|
|[centralops.net](https://centralops.net/co/),<br>Email Dossier|[Kind of](https://centralops.net/co/EmailDossier.aspx?email=test@example.com")|Confidence 3 - SMTP (Highest by tool)|2017|[HexValidEmail result](https://hexillion.com/docs/guides/HexValidEmail/concepts/interpret.htm)|
|[check-mail.org](https://check-mail.org)|[Yes](https://check-mail.org/get-started/), freemium|Valid, do not block, domain risk 70|*none*|Paid service|
|[disify.com](https://disify.com/)|[Yes](https://docs.disify.com/#introduction)|Valid Email Address|2023|Passion project. mozmail.com switched to valid around Nov 2023|
|[fakecheck.email](https://fakecheck.email)|No|**Disposable domain**|*none*|Advertises block-disposable-email.com.|
|[fakefilter.net](https://fakefilter.net/static/)|[fakefilter.net/api/is/fakedomain](https://fakefilter.net/static/docs/restful/) (free)|Is not a fake domain, no details|2022|Community project for identifying fake emails|
|[ipqualityscore.com](https://www.ipqualityscore.com/)|[Yes](https://www.ipqualityscore.com/free-email-validation-test)|Not Valid, Disposable|2023|Focus on fraud prevention|
|[istempmail.com](https://www.istempmail.com/)|[www.istempmail.com/api/check](https://www.istempmail.com/api/check) (free to paid)|**blocks** when registering|2023|Side project into API|
|[kickbox.com](https://kickbox.com/)|[open.kickbox.com](https://open.kickbox.com) (free)|Not disposable|2023|Paid service to verify email lists|
|[neverbounce.com](https://neverbounce.com/)|Yes|Less than 1% chance of bounce|2023|Paid with free trial of bounce checking for list|
|[spamhaus.org](https://www.spamhaus.org)|Yes|Not blocked|2023|Non-profit preventing spam. The [Spamhaus DBL](https://www.spamhaus.org/faq/section/Spamhaus%20DBL) tracks domains, and is queried via DNS like `host mozmail.com.dbl.spamhaus.org`. A `not found: 3(NXDOMAIN)` means the domain is not on the blocklist.|
|[stopforumspam.com](https://www.stopforumspam.com)|[Yes](https://www.stopforumspam.com/usage)|domain is not blocked|*none*|Plugins for multiple forums, API, [downloads](https://www.stopforumspam.com/downloads) for toxic domains and IPs)|
|[testmail.top](https://testmail.top/en/)|[Yes](https://testmail.top/en/#api)|**On blacklist**|*none*|Donation supported|

# Lists of Sources

* [SaaSHub - Email Verification API Software](https://www.saashub.com/best-email-verification-api-software?context=apis) - Not processed, many services
* [Rackaid - The 8 Email Blacklists You Should Actually Care About](https://www.rackaid.com/blog/email-blacklists/) - Mostly IP blocks, but services may have domain blocks too
* [Github Search](https://github.com/search?q=%22mozmail.com%22+NOT+%22%40mozmail.com%22+NOT+%22.mozmail.com%22+NOT+%22domozmail.com%22&type=code) can find more instances
