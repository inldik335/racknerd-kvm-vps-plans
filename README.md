# RackNerd KVM VPS: Which Plan Do You Actually Need, Does the Price Hold at Renewal, and What Do the One-Click Apps Really Require? (Full Plan Table Included)

RackNerd's KVM VPS specials run from **$21.99 to $119.99 per year**, all billed annually: 1 GB at $21.99, 2 GB at $35.99, 4 GB at $59.99, 6 GB at $89.99, and 8 GB at $119.99. The 2 GB tier is the one RackNerd labels most popular, and the detail that changes the arithmetic is that these are **lifetime recurring** prices, so the renewal invoice shows the same number next year and the year after.

A cheap annual VPS usually means a cheap first year followed by a full-price second one. RackNerd's specials don't work that way, and that single policy is worth more than any spec bump in this price bracket.

> **Quick pick:** most self-hosters should take the **2 GB KVM VPS at $35.99/year** — 2 vCPU cores, 35 GB SSD, 5 TB of transfer. Running Ollama, AnythingLLM, LibreChat or Hermes Agent? Go **4 GB at $59.99/year**. Running OpenClaw? You need **8 GB at $119.99/year**; nothing smaller meets its floor.
> 👉 [Get the 2 GB KVM VPS at $35.99/year](https://bit.ly/RacKnerd)

Every plan in this lineup ships with the same backbone: KVM virtualization, SSD storage, a 1Gbps network port, one IPv4 address, full root access over SSH, instant provisioning after payment, and the ctrl control panel. Locations are selectable at checkout. There is no monthly billing option on the specials page, so the first charge covers a full twelve months.

## All five RackNerd KVM VPS specials, side by side

This is the complete set currently shown on RackNerd's specials page. Nothing is omitted, and there is no cheaper hidden tier.

| Plan | vCPU / RAM | SSD | Monthly transfer | Price (billed yearly) | Order |
| --- | --- | --- | --- | --- | --- |
| 1 GB KVM VPS | 1 core / 1 GB | 20 GB | 3 TB | $21.99/year | [ Take the 1 GB KVM VPS at $21.99/year](https://bit.ly/RacKnerd) |
| 2 GB KVM VPS | 2 cores / 2 GB | 35 GB | 5 TB | $35.99/year | [ Take the 2 GB KVM VPS at $35.99/year](https://bit.ly/RacKnerd) |
| 4 GB KVM VPS | 3 cores / 4 GB | 60 GB | 7 TB | $59.99/year | [ Take the 4 GB KVM VPS at $59.99/year](https://bit.ly/RacKnerd) |
| 6 GB KVM VPS | 6 cores / 6 GB | 100 GB | 12 TB | $89.99/year | [ Take the 6 GB KVM VPS at $89.99/year](https://bit.ly/RacKnerd) |
| 8 GB KVM VPS | 7 cores / 8 GB | 150 GB | 20 TB | $119.99/year | [ Take the 8 GB KVM VPS at $119.99/year](https://bit.ly/RacKnerd) |

The 4 GB tier is listed with **3 vCPU cores**. Some third-party pages that copy RackNerd's pricing still show 2 cores for that plan; the official page says 3.

Per-gigabyte, the 2 GB plan at $35.99 works out to roughly $18 per GB of RAM per year, and the 8 GB at $119.99 to about $15. The 1 GB plan is the worst value on that metric, which tells you it exists to hit a price point rather than to be the smart buy.

## What renewal actually costs, and the one term that matters most

RackNerd's own FAQ states it plainly: *"These RackNerd VPS specials are lifetime recurring. You can renew at the same rate for as long as you decide to keep the service."* Year two of the 2 GB plan is $35.99. Year three is $35.99. There is no introductory rate that expires.

That matters because the low-end VPS market is full of first-year teasers that double on renewal, and the quoted price tells you nothing about what you'll pay once the site is live and migrating is annoying.

The flip side of a locked annual price is commitment. There is no monthly version of these specials, and RackNerd's knowledgebase is direct about refunds: *"Per our terms of service, we do not offer refunds or have a money back guarantee."* So the first payment is a twelve-month commitment, not a trial. Budget accordingly: $21.99 is under $2 a month, but it leaves your account in one go.

Nothing on the specials page requires a promo code, and the listed prices are the prices. If a coupon site offers you "30% off RackNerd VPS", treat it as expired or fabricated.

## Pick your plan by the app you intend to run

RackNerd publishes memory floors for its ctrl one-click apps, and they are the most useful sizing guide in the entire listing, because they come from the vendor rather than from guesswork.

| One-click app | Minimum RAM |
| --- | --- |
| OpenClaw | 8 GB |
| Hermes Agent | 4 GB |
| AnythingLLM | 4 GB |
| Ollama | 4 GB |
| LibreChat | 4 GB |
| n8n | 2 GB (comfortable) |
| Coolify | 2 GB (comfortable) |

Read that table as a hard filter:

- **OpenClaw → 8 GB at $119.99/year.** The 4 GB and 6 GB plans fall short. There is no way around this one; undersizing it means the app either won't install or will thrash.
- **Ollama, AnythingLLM, LibreChat, Hermes Agent → 4 GB at $59.99/year.** Note that 4 GB is the floor, not a comfortable ceiling. Small models on Ollama will run; larger ones want the 8 GB plan.
- **n8n, Coolify, Docker + Portainer, a WordPress site → 2 GB at $35.99/year.** This is the tier where small stacks stop feeling cramped.
- **1 GB at $21.99/year → no one-click AI app qualifies.** Use it for a proxy, a tunnel endpoint, a single low-traffic site, a DNS box, or a monitoring node. RackNerd doesn't list a single one-click app that officially runs in 1 GB.

If you're planning an AI side project rather than a website, the 4 GB plan is the realistic entry point, not the 2 GB.

👉 [Set up the 4 GB KVM VPS at $59.99/year for Ollama, AnythingLLM or LibreChat](https://bit.ly/RacKnerd)

Software outside the catalog is not a problem. Full root SSH access means you install whatever you want, and the catalog covers Docker + Portainer, CyberPanel, CloudPanel, AdminBolt, n8n, Coolify and the AI tools above. Credentials for a one-click install appear inside ctrl once the app finishes.

## ctrl is the panel now, and that's why older tutorials confuse people

Every special includes **ctrl**, RackNerd's own control panel, and it handles the day-to-day work: power on/off, reboot, OS reinstall, an out-of-band HTML5 VNC console, root password reset, bandwidth graphs, inbound filtering through the ctrl Network Firewall, plan upgrades, and the one-click app catalog. RackNerd runs an interactive demo of it that you can click through without an account, which is a reasonable way to check whether the interface makes sense to you before paying.

If you go looking for setup instructions, you'll run into guides that name **SolusVM** as the panel. Those are older pages and third-party copies; RackNerd's current product page and its own blog both describe ctrl. The practical consequence is minor: your VPS login details arrive by email after deployment and live in the client area, so look there rather than hunting for a SolusVM URL that isn't part of the current setup.

Reinstalling the OS later is a ctrl action, not a support ticket. Custom ISO installs are the exception and do require a ticket.

## Locations, operating systems, and the limits worth knowing before you pay

**Operating systems:** CentOS, Rocky Linux, AlmaLinux, Fedora, Debian, or Ubuntu at order time. Custom ISOs on request via ticket, and the VNC console lets you mount your own media if you'd rather do it yourself.

**Locations:** RackNerd lets you pick a datacenter close to your users, but the specials page doesn't publish a count. Third-party pages list Los Angeles, San Jose, Seattle, Dallas, Atlanta, Chicago, New Jersey, New York, Ashburn, Amsterdam and France; other sources claim around 20. Since RackNerd doesn't state a number on the product page, check the location dropdown at checkout and ping a test IP before committing if latency is critical.

**IPv6:** Multiple third-party guides say the Los Angeles and France locations hand out up to 100 free IPv6 addresses on request via ticket. This isn't stated on the specials page, so treat it as likely but unconfirmed and open a ticket after ordering to ask.

**Unmanaged:** This is the term that disqualifies a lot of buyers. RackNerd supports the platform: hardware, power, network, provisioning. It does not configure your firewall, debug your WordPress plugins, or clean up a compromised install. ctrl makes the routine operations click-easy, but if you can't comfortably use SSH, this price tier is the wrong place to learn.

**Backups:** The specials page doesn't advertise automated backups or snapshots. Set up your own off-server backup routine from day one, especially for anything holding data you'd miss.

## Who should not buy one of these

Skip RackNerd's KVM VPS specials if any of these describe you:

1. **You want managed hosting.** Someone to fix your stack, not just the platform.
2. **You need cPanel included.** cPanel appears in RackNerd's shared and reseller lines, not bundled with these VPS plans; CyberPanel and CloudPanel are the free one-click alternatives here.
3. **You need Windows.** Windows VPS is a separate product line with separate pricing, not part of these specials.
4. **You want to test for a month.** Annual billing plus no refunds makes this an expensive experiment. Pay monthly somewhere else first if you're unsure.
5. **You need live chat or phone support.** Support here is ticket-based, around the clock.

For everyone else, the risk is bounded: a year of root access on a KVM slice costs less than two coffees a month at the entry tier.

## Common questions

**Will the price go up at renewal?** No. RackNerd's FAQ says these specials are lifetime recurring at the same rate for as long as you keep the service.

**Can I upgrade to a bigger plan later?** Yes, upgrades to the next tier are supported. Expect roughly a minute of downtime for the reboot that applies it.

**How fast is provisioning?** Your VPS is set up right after payment, so you can be logged in within minutes.

**Can I switch operating systems after ordering?** Yes, from ctrl, as often as you like. Custom ISOs need a ticket.

**Is IPv4 included?** Yes, one IPv4 address with every plan, plus full root access and a 1Gbps port.

**Can I run Docker or WordPress?** Yes. Docker + Portainer is a one-click install in ctrl; WordPress fits AdminBolt, CyberPanel or CloudPanel, or you install it yourself over SSH.

**Is it reliable?** Trustpilot shows 4.1 out of 5 across 371 reviews at the time of checking, with reviewers citing fast ticket replies, multi-year stability, and 100% uptime recorded by their own monitoring. Those are user accounts, not independent benchmarks, and low-end VPS nodes can get crowded at times.

## Before you click order

Match the job to the tier and stop there:

- **A proxy, tunnel, single small site, or monitoring box → 1 GB at $21.99/year.**
- **n8n, Coolify, Docker containers, a normal WordPress site → 2 GB at $35.99/year.**
- **Ollama, AnythingLLM, LibreChat, Hermes Agent → 4 GB at $59.99/year, and consider 8 GB if you want headroom.**
- **OpenClaw, or several of the above on one box → 8 GB at $119.99/year.**

Two things to confirm on the order form: that you're selecting annual billing and will be charged the full year up front, and that you accept this is an unmanaged server where the operating system is your responsibility. If both are fine, pick your datacenter, complete the order, and check your email for the ctrl login.

👉 [Compare all five RackNerd KVM VPS specials and pick your datacenter](https://bit.ly/RacKnerd)
# RackNerd KVM VPS: Which Plan Do You Actually Need, Does the Price Hold at Renewal, and What Do the One-Click Apps Really Require? (Full Plan Table Included)

RackNerd's KVM VPS specials run from **$21.99 to $119.99 per year**, all billed annually: 1 GB at $21.99, 2 GB at $35.99, 4 GB at $59.99, 6 GB at $89.99, and 8 GB at $119.99. The 2 GB tier is the one RackNerd labels most popular, and the detail that changes the arithmetic is that these are **lifetime recurring** prices, so the renewal invoice shows the same number next year and the year after.

A cheap annual VPS usually means a cheap first year followed by a full-price second one. RackNerd's specials don't work that way, and that single policy is worth more than any spec bump in this price bracket.

> **Quick pick:** most self-hosters should take the **2 GB KVM VPS at $35.99/year** — 2 vCPU cores, 35 GB SSD, 5 TB of transfer. Running Ollama, AnythingLLM, LibreChat or Hermes Agent? Go **4 GB at $59.99/year**. Running OpenClaw? You need **8 GB at $119.99/year**; nothing smaller meets its floor.
> 👉 [Get the 2 GB KVM VPS at $35.99/year](https://bit.ly/RacKnerd)

Every plan in this lineup ships with the same backbone: KVM virtualization, SSD storage, a 1Gbps network port, one IPv4 address, full root access over SSH, instant provisioning after payment, and the ctrl control panel. Locations are selectable at checkout. There is no monthly billing option on the specials page, so the first charge covers a full twelve months.

## All five RackNerd KVM VPS specials, side by side

This is the complete set currently shown on RackNerd's specials page. Nothing is omitted, and there is no cheaper hidden tier.

| Plan | vCPU / RAM | SSD | Monthly transfer | Price (billed yearly) | Order |
| --- | --- | --- | --- | --- | --- |
| 1 GB KVM VPS | 1 core / 1 GB | 20 GB | 3 TB | $21.99/year | [ Take the 1 GB KVM VPS at $21.99/year](https://bit.ly/RacKnerd) |
| 2 GB KVM VPS | 2 cores / 2 GB | 35 GB | 5 TB | $35.99/year | [ Take the 2 GB KVM VPS at $35.99/year](https://bit.ly/RacKnerd) |
| 4 GB KVM VPS | 3 cores / 4 GB | 60 GB | 7 TB | $59.99/year | [ Take the 4 GB KVM VPS at $59.99/year](https://bit.ly/RacKnerd) |
| 6 GB KVM VPS | 6 cores / 6 GB | 100 GB | 12 TB | $89.99/year | [ Take the 6 GB KVM VPS at $89.99/year](https://bit.ly/RacKnerd) |
| 8 GB KVM VPS | 7 cores / 8 GB | 150 GB | 20 TB | $119.99/year | [ Take the 8 GB KVM VPS at $119.99/year](https://bit.ly/RacKnerd) |

The 4 GB tier is listed with **3 vCPU cores**. Some third-party pages that copy RackNerd's pricing still show 2 cores for that plan; the official page says 3.

Per-gigabyte, the 2 GB plan at $35.99 works out to roughly $18 per GB of RAM per year, and the 8 GB at $119.99 to about $15. The 1 GB plan is the worst value on that metric, which tells you it exists to hit a price point rather than to be the smart buy.

## What renewal actually costs, and the one term that matters most

RackNerd's own FAQ states it plainly: *"These RackNerd VPS specials are lifetime recurring. You can renew at the same rate for as long as you decide to keep the service."* Year two of the 2 GB plan is $35.99. Year three is $35.99. There is no introductory rate that expires.

That matters because the low-end VPS market is full of first-year teasers that double on renewal, and the quoted price tells you nothing about what you'll pay once the site is live and migrating is annoying.

The flip side of a locked annual price is commitment. There is no monthly version of these specials, and RackNerd's knowledgebase is direct about refunds: *"Per our terms of service, we do not offer refunds or have a money back guarantee."* So the first payment is a twelve-month commitment, not a trial. Budget accordingly: $21.99 is under $2 a month, but it leaves your account in one go.

Nothing on the specials page requires a promo code, and the listed prices are the prices. If a coupon site offers you "30% off RackNerd VPS", treat it as expired or fabricated.

## Pick your plan by the app you intend to run

RackNerd publishes memory floors for its ctrl one-click apps, and they are the most useful sizing guide in the entire listing, because they come from the vendor rather than from guesswork.

| One-click app | Minimum RAM |
| --- | --- |
| OpenClaw | 8 GB |
| Hermes Agent | 4 GB |
| AnythingLLM | 4 GB |
| Ollama | 4 GB |
| LibreChat | 4 GB |
| n8n | 2 GB (comfortable) |
| Coolify | 2 GB (comfortable) |

Read that table as a hard filter:

- **OpenClaw → 8 GB at $119.99/year.** The 4 GB and 6 GB plans fall short. There is no way around this one; undersizing it means the app either won't install or will thrash.
- **Ollama, AnythingLLM, LibreChat, Hermes Agent → 4 GB at $59.99/year.** Note that 4 GB is the floor, not a comfortable ceiling. Small models on Ollama will run; larger ones want the 8 GB plan.
- **n8n, Coolify, Docker + Portainer, a WordPress site → 2 GB at $35.99/year.** This is the tier where small stacks stop feeling cramped.
- **1 GB at $21.99/year → no one-click AI app qualifies.** Use it for a proxy, a tunnel endpoint, a single low-traffic site, a DNS box, or a monitoring node. RackNerd doesn't list a single one-click app that officially runs in 1 GB.

If you're planning an AI side project rather than a website, the 4 GB plan is the realistic entry point, not the 2 GB.

👉 [Set up the 4 GB KVM VPS at $59.99/year for Ollama, AnythingLLM or LibreChat](https://bit.ly/RacKnerd)

Software outside the catalog is not a problem. Full root SSH access means you install whatever you want, and the catalog covers Docker + Portainer, CyberPanel, CloudPanel, AdminBolt, n8n, Coolify and the AI tools above. Credentials for a one-click install appear inside ctrl once the app finishes.

## ctrl is the panel now, and that's why older tutorials confuse people

Every special includes **ctrl**, RackNerd's own control panel, and it handles the day-to-day work: power on/off, reboot, OS reinstall, an out-of-band HTML5 VNC console, root password reset, bandwidth graphs, inbound filtering through the ctrl Network Firewall, plan upgrades, and the one-click app catalog. RackNerd runs an interactive demo of it that you can click through without an account, which is a reasonable way to check whether the interface makes sense to you before paying.

If you go looking for setup instructions, you'll run into guides that name **SolusVM** as the panel. Those are older pages and third-party copies; RackNerd's current product page and its own blog both describe ctrl. The practical consequence is minor: your VPS login details arrive by email after deployment and live in the client area, so look there rather than hunting for a SolusVM URL that isn't part of the current setup.

Reinstalling the OS later is a ctrl action, not a support ticket. Custom ISO installs are the exception and do require a ticket.

## Locations, operating systems, and the limits worth knowing before you pay

**Operating systems:** CentOS, Rocky Linux, AlmaLinux, Fedora, Debian, or Ubuntu at order time. Custom ISOs on request via ticket, and the VNC console lets you mount your own media if you'd rather do it yourself.

**Locations:** RackNerd lets you pick a datacenter close to your users, but the specials page doesn't publish a count. Third-party pages list Los Angeles, San Jose, Seattle, Dallas, Atlanta, Chicago, New Jersey, New York, Ashburn, Amsterdam and France; other sources claim around 20. Since RackNerd doesn't state a number on the product page, check the location dropdown at checkout and ping a test IP before committing if latency is critical.

**IPv6:** Multiple third-party guides say the Los Angeles and France locations hand out up to 100 free IPv6 addresses on request via ticket. This isn't stated on the specials page, so treat it as likely but unconfirmed and open a ticket after ordering to ask.

**Unmanaged:** This is the term that disqualifies a lot of buyers. RackNerd supports the platform: hardware, power, network, provisioning. It does not configure your firewall, debug your WordPress plugins, or clean up a compromised install. ctrl makes the routine operations click-easy, but if you can't comfortably use SSH, this price tier is the wrong place to learn.

**Backups:** The specials page doesn't advertise automated backups or snapshots. Set up your own off-server backup routine from day one, especially for anything holding data you'd miss.

## Who should not buy one of these

Skip RackNerd's KVM VPS specials if any of these describe you:

1. **You want managed hosting.** Someone to fix your stack, not just the platform.
2. **You need cPanel included.** cPanel appears in RackNerd's shared and reseller lines, not bundled with these VPS plans; CyberPanel and CloudPanel are the free one-click alternatives here.
3. **You need Windows.** Windows VPS is a separate product line with separate pricing, not part of these specials.
4. **You want to test for a month.** Annual billing plus no refunds makes this an expensive experiment. Pay monthly somewhere else first if you're unsure.
5. **You need live chat or phone support.** Support here is ticket-based, around the clock.

For everyone else, the risk is bounded: a year of root access on a KVM slice costs less than two coffees a month at the entry tier.

## Common questions

**Will the price go up at renewal?** No. RackNerd's FAQ says these specials are lifetime recurring at the same rate for as long as you keep the service.

**Can I upgrade to a bigger plan later?** Yes, upgrades to the next tier are supported. Expect roughly a minute of downtime for the reboot that applies it.

**How fast is provisioning?** Your VPS is set up right after payment, so you can be logged in within minutes.

**Can I switch operating systems after ordering?** Yes, from ctrl, as often as you like. Custom ISOs need a ticket.

**Is IPv4 included?** Yes, one IPv4 address with every plan, plus full root access and a 1Gbps port.

**Can I run Docker or WordPress?** Yes. Docker + Portainer is a one-click install in ctrl; WordPress fits AdminBolt, CyberPanel or CloudPanel, or you install it yourself over SSH.

**Is it reliable?** Trustpilot shows 4.1 out of 5 across 371 reviews at the time of checking, with reviewers citing fast ticket replies, multi-year stability, and 100% uptime recorded by their own monitoring. Those are user accounts, not independent benchmarks, and low-end VPS nodes can get crowded at times.

## Before you click order

Match the job to the tier and stop there:

- **A proxy, tunnel, single small site, or monitoring box → 1 GB at $21.99/year.**
- **n8n, Coolify, Docker containers, a normal WordPress site → 2 GB at $35.99/year.**
- **Ollama, AnythingLLM, LibreChat, Hermes Agent → 4 GB at $59.99/year, and consider 8 GB if you want headroom.**
- **OpenClaw, or several of the above on one box → 8 GB at $119.99/year.**

Two things to confirm on the order form: that you're selecting annual billing and will be charged the full year up front, and that you accept this is an unmanaged server where the operating system is your responsibility. If both are fine, pick your datacenter, complete the order, and check your email for the ctrl login.

👉 [Compare all five RackNerd KVM VPS specials and pick your datacenter](https://bit.ly/RacKnerd)
