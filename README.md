# tutorial-setup-linux-VPS-server-with-apache
a step by step tutorial of how to do a basic setup of a linux VPS server with apache. For beginners

This is a basic setup of a Linux server, explained step by step. This is geared towards complete beginners. Please read this page completely before moving on to the tutorial (in this repo's Wiki - link below)

## Disclaimer
This is just a guide. As the license says, I am not responsible for any damages, security breaches, etc - it is up to YOU to ensure your server is set up appropriately and securely for YOUR purpose. 

I have made a good faith effort to ensure sensible choices are made, but understand that this tutorial is just a starting point. The suggested defaults here may not be appropriate for your application.

## Trade-offs you should be aware of before starting
This guide is aimed for convenience and speed of setup, and I have traded that off against a bit of security. Specifically, I illustrate the use of the free and open source Webmin panel here. Webmin itself is not inherently insecure compared to any other admin panel, but ANY additional software that is not strictly necessary could represent a potential security hole, whether present or future. However, for a beginner, I believe the trade-off is worth the convenience. 

If you are not comfortable with this, and if you have experience with linux, you might like to follow along without Webmin and instead do the Webmin-dependent steps purely on the command line.
