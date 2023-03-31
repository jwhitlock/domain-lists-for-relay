[Firefox Relay](https://relay.firefox.com) provides emails masks for
[Firefox Accounts](accounts.firefox.com/) users with a domain of `mozmail.com`,
or (for paying users) a subdomain of `mozmail.com`. Some services deny
registration or avoid emailing
[disposable email addresses](https://en.wikipedia.org/wiki/Disposable_email_address).
We try to keep `mozmail.com` off these deny lists, so that our users can use
their email more places.

# Disposable domain lists

These repositories maintain lists of disposable email addresses.

|Name|Link|Has mozmail.com?|Age|Note|
|:---|:---|:---------------|:--|:---|
|[7c/fakefilter](./7c/fakefilter)|[GitHub](https://github.com/7c/fakefilter)|No|Active|Looks for temp and fake emails in registrations, backend for [fakefilter.net](https://fakefilter.net/static/docs/restful/)|
|[FGRibreau/mailchecker](./FGRibreau/mailchecker)|[GitHub](https://github.com/fgribreau/mailchecker)|No|Active|Multi-language email validator and temp email detector|
|[GeroldSetz/emailondeck.com-domains](./GeroldSetz/emailondeck.com-domains)|[GitHub](https://github.com/GeroldSetz/emailondeck.com-domains)|No|Jun 2021|Follows [www.block-disposable-email.com](https://www.block-disposable-email.com/cms/)|
|[MattKetmo/EmailChecker](./MattKetmo/EmailChecker)|[GitHub](https://github.com/MattKetmo/EmailChecker)|No|Feb 2023|PHP disposable email detector|
|[adamloving/temporary-email-address-domains](./adamloving/temporary-email-address-domains)|[Gist](https://gist.github.com/adamloving/4401361)|No|Jul 2019|Comments advertise other services|
|[amieiro/disposable-email-domains](./amieiro/disposable-email-domains)|[GitHub](https://github.com/amieiro/disposable-email-domains)|**In [allow](https://github.com/amieiro/disposable-email-domains/blob/bf5361e37ab0c2616edd5c2cd50556fe6f993965/allowDomains.txt#L335) and [deny domains](https://github.com/amieiro/disposable-email-domains/blob/bf5361e37ab0c2616edd5c2cd50556fe6f993965/denyDomains.txt#95160) (line 95160)**|Active|Combines lists from other sources|
|[auth0-signals/disposable-email-domains](./auth0-signals/disposable-email-domains)|[GitHub](https://github.com/auth0-signals/disposable-email-domains)|No|Aug 2020|Submissions to defunct site apility.io|
|[codeAshu/fakemails.txt](./codeAshu/fakemails.txt)|[Gist](https://gist.github.com/codeAshu/ebade8f300809a4079220f771265b0c4)|No|July 2018|List of domains, comments suggest changes|
|[daisy1754/jp-disposable-emails](./daisy1754/jp-disposable-emails)|[GitHub](https://github.com/daisy1754/jp-disposable-emails/)|No|Jun 2021|List of domains from other sources|
|[disposable-email-domains/disposable-email-domains](./disposable-email-domains/disposable-email-domains)|[GitHub](https://github.com/disposable-email-domains/disposable-email-domains)|In [allow list](https://github.com/disposable-email-domains/disposable-email-domains/blob/3ff014e9a26f29b9e60ac2b3633747f4de03cf83/allowlist.conf#L119)|Dec 2022|block and allow list|
|[disposable-email-domains/python-disposable-email-domains](./disposable-email-domains/python-disposable-email-domains)|[GitHub](https://github.com/disposable-email-domains/python-disposable-email-domains)|In [allow list](https://github.com/disposable-email-domains/python-disposable-email-domains/blob/98537f0a155348052f33d93fb24d0b2633ddfb7a/disposable_email_domains/__init__.py#L120)|Active|Above lists as Python sets|
|[disposable/disposable-email-domains](./disposable/disposable-email-domains)|[GitHub](https://github.com/disposable/disposable-email-domains)|**In [domains list](https://github.com/disposable/disposable-email-domains/blob/master/domains.txt)**|Active|Text and JSON lists of domains|
|[disposable/disposable](./disposable/disposable)|[GitHub](https://github.com/disposable/disposable)|No|Active|Tools for working with domain lists, with list of external sources|
|[disposable/static-disposable-lists](./disposable/static-disposable-lists)|[GitHub](https://github.com/disposable/static-disposable-lists/)|No|Apr 2022|Email domains that can't be dynamically updated|
|[ivolo/disposable-email-domains](./ivolo/disposable-email-domains)|[GitHub](https://github.com/ivolo/disposable-email-domains)|No|Sep 2022|Source for [Kickbox.com API](https://open.kickbox.com/v1/disposable/mailinator.com)|
|[jamesonev/disposableEmailDomains.txt](./jamesonev/disposableEmailDomains.txt)|[Gist](https://gist.github.com/jamesonev/7e188c35fd5ca754c970e3a1caf045ef/)|No|July 2020|List from defunct block-temporary-email.com|
|[jespernissen/disposable-maildomain-list](./jespernissen/disposable-maildomain-list)|[GitHub](https://github.com/jespernissen/disposable-maildomain-list)|No|Aug 2021|List of domains|
|[kslr/disposable-email-domains](./kslr/disposable-email-domains)|[GitHub](https://github.com/kslr/disposable-email-domains)|**In [list](https://github.com/kslr/disposable-email-domains/blob/3746544f88bf3e4ebb546c52110186ebd69ea2b7/list.txt) (line 111863)**|Active|Text and JSON lists of domains|
|[maximeg/email_inquire](./maximeg/email_inquire)|[GitHub](https://github.com/maximeg/email_inquire)|No|Jan 2020|Ruby library to validate and fix emails, detect disposable emails|
|[micke/valid_email2](./micke/valid_email2)|[GitHub](https://github.com/micke/valid_email2)|**In [disposable email domains](https://github.com/micke/valid_email2/blob/bd01c20900941de4e018a98a692f6ec5e64cacbb/config/disposable_email_domains.txt) (line 87313)**|Active|Ruby gem to validate emails, detect disposable emails|
|[smudge/freemail](./smudge/freemail)|[GitHub](https://github.com/smudge/freemail)|No|Oct 2022|Ruby port of willwhite's freemail|
|[stopforumspam/disposable_email_domains](./stopforumspam/disposable_email_domains)|[GitHub](https://github.com/stopforumspam/disposable_email_domains/)|**On [blacklist](https://github.com/stopforumspam/disposable_email_domains/blob/master/blacklist.txt#L66971)**|Oct 2020|List of domains|
|[wesbos/burner-email-providers](./wesbos/burner-email-providers)|[GitHub](https://github.com/wesbos/burner-email-providers)|No|Active|List of emails, links to Firefox Relay|
|[willwhite/freemail](./willwhite/freemail)|[GitHub](https://github.com/willwhite/freemail)|No|July 2020|List and Node.js module|

# Services

These provide plugins and an API for checking an email address.

|Main Site|API|mozmail.com result|Note|
|:--------|:--|:-----------------|:---|
|[kickbox.com](https://kickbox.com/)|[open.kickbox.com](https://open.kickbox.com) (free)|Not disposable|Paid service to verify email lists|
|[fakefilter.net](https://fakefilter.net/static/)|[fakefilter.net/api/is/fakedomain](https://fakefilter.net/static/docs/restful/) (free)|Is not a fake domain, no details|Community project for identifying fake emails|
|[block-disposable-email.com](https://www.block-disposable-email.com/cms/)|[api.block-disposable-email.com/easyapi](https://www.block-disposable-email.com/cms/help-and-usage/easy-api/) (free registration), [Try it](https://www.block-disposable-email.com/cms/try/) (with CAPTCHA)|**`fake-email-address`, block it**|Provides API with [free registration](https://www.block-disposable-email.com/cms/register/)|
|[stopforumspam.com](https://www.stopforumspam.com)|[api.stopforumspam.org](https://www.stopforumspam.com/usage)|domain is not blocked|Plugins for multiple forums, API|
