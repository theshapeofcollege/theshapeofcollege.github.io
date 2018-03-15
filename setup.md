# How to make and deploy websites

1. Create github repo, clone locally empty repo x
2. Copy template site into repo, push x
3. Modify template site as desired
4. Implement mobile formatting

Sitemap and indexing (todo)
https:// cloudflare (todo)
og tags and web tiles (todo)
domain setup (todo) and catchall email
email forwarding via mailgun

Step 1: Signup for a free account in mailgun.com

Step 2: Log into your account in Mailgun and add a domain from the top menubar. Once your domain is added, you will see that mailgun gives you a few MX records and TXT records to be added for your domain, for both successful email forwarding and verification of the domain.

Step 3: Now go to your domain's DNS panel and add those MX records and TXT records provided by Mailgun.

Step 4: This is the final step. Log into your Mailgun account and go to Routes section from the top menu. Now add as many routes as you want. For example, if your domain is example.com and you want all the mails sent to hello@example.com to be forwarded to doctor@who.com then create a route like this screenshot, and you are done :)

# Extras

- Mailchimp subscription: make account, set up list, embed form.
-
