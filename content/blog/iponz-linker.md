+++
date = '2025-10-26T14:54:19+13:00'
draft = false 
title = 'IPONZ Linker'
+++
Have you ever wanted to share a link to your favourite NZ Intellectual Property right? Probably not, but if you're in the IP profession you may have realised that this was not possible at all 😢

The URL when viewing a record on an IPONZ register looks something like this:
https://app.iponz.govt.nz/app/Extra/IP/Mutual/Browse.aspx?sid=638957163299224953

Notice that there is no case number to be seen. When you look up a record, that action is stored on the server as session state, and you're redirected away from the search page. Then you're connected back to your session via a session ID to view the record. This means the URL is totally useless as a permanent link, which seems suboptimal for a public register.

Meanwhile, the patent offices of Australia and Europe have advanced stateless web technology all figured out:\
https://register.epo.org/application?number=EP07075884
https://ipsearch.ipaustralia.gov.au/patents/2016201249

If you have read this far then you may be thrilled to hear that I've taken it upon myself to fix this dire situation for our country. The [IPONZ Linker Chrome extension](https://chromewebstore.google.com/detail/iponz-linker/ekoaiaoikoakfaddefogbojeokkehngk) lets you create links to any IPONZ record using a sensible format, and it can link search field combinations too in case you've ever experienced the ennui of mindlessly filling out fields for a watching search that no one will read.

If every NZ IP professional installs it then we can feel joy again through sending each other links to our favourite patents, trade marks, and designs. For example:\
https://iponz.link?register=tm&number=1259120

IPONZ please make my extension redundant sometime before the next Patents Act drops xoxo
