# Revenue Dashboard for your Active payment links

[![janwilmake/openstripedashboard context](https://badge.forgithub.com/janwilmake/openstripedashboard)](https://uithub.com/janwilmake/openstripedashboard) [![janwilmake/openstripedashboard context](https://b.lmpify.com)](https://lmpify.com/?q=https://uithub.com/janwilmake/openstripedashboard)

How it's made:

- [![](https://b.lmpify.com/Backend)](https://lmpify.com/httpslmpifycomf-1u5jbu0)
- [![](https://b.lmpify.com/Frontend)](https://lmpify.com/httpspastebincon-52uxzh0)

NB: this app pulls all transactions from all **active** payment links from the stripe api and this can take a while if you have a lot of them. Please [reach out](https://x.com/janwilmake/status/1929840655800381525) if you have a different need and/or ideas to make this better.

Also, if you have lots of programmatic payment links, you can deactivate them with a script [like this](https://x.com/janwilmake/status/1929832481257144509)

TODO:

- Also extract payment intents and % conversion per payment link if possible. This gives us on-page conversion %
- Also extract cross-payment-link customers: top 10 customers that used the most unique payment links
- Extract recurring customers: customers that appear twice or more on a single payment link. how much % is recurring? how much time on average between first purchase and second purchase?
