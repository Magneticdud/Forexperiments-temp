+++
title = "I'm done with the migration... finally?"
date = 2024-03-03
author = "Magnetic_dud"
tags = [ "Website"]
+++

I finally managed to end the migration from WordPress on the English website too. I [took over one year](/2023-02-14-new-platform) because the old host wasn't supporting CloudFlare and so I was stuck with WordPress 😅

Now that everything is static and there's nowhere to login, the bots can continue to have fun bruteforcing /wp-admin for inexistant users.

Also, my server does not need to re-render the same page over and over and over to different users. Once I published, it's done, the page it's a static file that won't be rendered anymore. Much faster 😎.

Except... I noticed that in the last year, the developer of my theme did some breaking changes, so I might need to carefully check what's going on before approving the latest version upgrade. Namely, hyperlinked images aren't supported anymore... hope I never used them anywhere in this blog...
