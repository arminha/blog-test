+++
title = "Sealing Off Holes in the Great Firewall"
date = 2015-04-03T17:45:41+02:00

[taxonomies]
categories = ["technology"]
+++

Two weeks ago there was a [hacker attack](http://sinosphere.blogs.nytimes.com/2015/03/20/hackers-attack-greatfire-org-a-workaround-for-websites-censored-in-china/) on [GreatFire.org](https://en.greatfire.org/). A website which monitors content blocked by the Great Firewall and offers tools to subvert it.

<!-- more -->
A week later we heard about a [large scale DDoS attack on GitHub](https://github.com/blog/1981-large-scale-ddos-attack-on-github-com). GitHub said:

>Based on reports we've received, we believe the intent of this attack is to convince us to remove a specific class of content.

GreatFire.org itself has a GitHub page at [github.com/greatfire](https://github.com/greatfire) with the source for their page and proxy servers.
Apparently the DDoS attack was performed by [hijacking web traffic for Baidu ads and redirecting it to GitHub](http://www.nytimes.com/2015/03/31/technology/china-appears-to-attack-github-by-diverting-web-traffic.html).
A more technical analysis of the attack can be found [here](http://insight-labs.org/?p=1682), [here](http://www.netresec.com/?page=Blog&month=2015-03&post=China%27s-Man-on-the-Side-Attack-on-GitHub) and [here](http://blog.erratasec.com/2015/04/pin-pointing-chinas-attack-against.html).

All together an interesting piece of how China tries to seal off holes in the Great Firewall.

On a side note: some days ago I found a tool to easily set up your own proxy server. Kind of like a poor man's VPN. It's called [sshuttle](https://github.com/apenwarr/sshuttle). I will test it next time I'm behind the Great Firewall.
