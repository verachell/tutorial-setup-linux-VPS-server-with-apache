# tutorial-setup-linux-VPS-server-with-apache
a step by step tutorial of how to do a basic setup of a linux VPS server with apache. For beginners

This is a basic setup of a Linux server, explained step by step. This is geared towards complete beginners. Please read this page completely before moving on to the tutorial (in this repo's Wiki - link below)

This tutorial will work for hosting 1 or more domain names on a single server. Technically, you could just host it without a domain name at the IP address, but if you want SSL (which you presumably do), you'll want a domain name.

## Disclaimer
This is just a guide. As the license says, I am not responsible for any damages, security breaches, etc from any security holes in the setup in this tutorial. It is up to YOU to ensure your server is set up appropriately and securely for YOUR purpose. 

I have made a good faith effort to ensure sensible choices are made, but understand that this tutorial is just a starting point. The suggested defaults here may not be appropriate for your application.

## Trade-offs you should be aware of
This guide is aimed for convenience and speed of setup, and I have traded that off against a bit of security. Specifically, I illustrate the use of the free and open source Webmin panel here. Webmin itself is not inherently insecure compared to any other admin panel, but ANY additional software that is not strictly necessary could represent a potential security hole, whether present or future. However, for a beginner, I believe the trade-off is worth the convenience. 

If you are not comfortable with this, and if you have experience with linux, you might like to follow along this tutorial without Webmin and instead do the Webmin-dependent steps purely on the command line.

## Start the tutorial
The tutorial is on this repository's wiki page at https://github.com/verachell/tutorial-setup-linux-VPS-server-with-apache/wiki

## If you run into problems
I've covered troubleshooting in places where I think things could go wrong and I've tested this tutorial out on a brand-new install. That said, if you get stuck or if something is wrong, please raise an issue on the repo (preferably). Alternatively you can email me (I *think* my email address is visible to logged-in users?). Once a problem is brought to my attention. I will do my best to help. If you manage to get stuck, others might too, so raising an issue helps make this tutorial better for everyone.
