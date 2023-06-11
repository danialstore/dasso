-----

1. Find and replace API site in checker.php
- See tutorial at https://crax.tube/watch/how-to-make-cc-checker-tutorial-2-req-stripe-cvv-cnn-2-4_P5Gzt62TqmstNNc.html

2. This file includes 4 proxy options, comment in or out the option you choose
- No proxy
- Proxy.txt (Copy your proxies and paste inside proxy.txt)
- Webshare (Register for 10 free proxies at https://webshare.io, pay for more proxies)
- Hydra Proxy (Fully paid service, choose rotation by "Request", not "Sticky" on Hydra panel)

The default option is Webshare. This is not your email and password you choose upon registration, see Webshare proxy page for proxy username and password

Find below lines in checker.php and replace with your details

$webshareuserpass = '11111-rotate:22222';

Replace 11111 with your Webshare proxy username and 22222 with your Webshare proxy password, don't remove that "-rotate"

That is the only step needed to use Webshare

-----

Hosting

1. Ksweb Pro (Android phone or emulator)
- Ksweb Pro v3.971, it's an Android app, buy or search for modded version.
- Original version can be found at https://ksweb.en.uptodown.com/android/download/3276419

2. Xampp (PC or Mac)

3. Internet (Web hosting, VPS or dedicated server)