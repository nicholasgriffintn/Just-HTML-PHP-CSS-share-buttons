# Just HTML/PHP/CSS share buttons

So I have noticed that a lot of websites still use a ton of javascript and often they use third-parties to get share buttons on their websites.

In a world where we need the web to be fast, this isn't going to work, too much JS will slow down your pages, and not only will the use of third-parties slow down your site, it will also lead to distrust of your users, who are often being tracked by these services.

Using just HTML, all you need to do is add the CSS code to your main stylesheet and then pop the HTML code in the spot where you want the buttons to be shown.

This code will not track users (until the user actually clicks the button of course), it will not load JavaScript (aside from the onlick links and the FontAwesome icons, I would recommend switching FontAwesome for FortAwesome in a live install though), and it will not link your site to any more third parties, quite simply, it's a cool way of showing some HTML links.

(This code has been built for a WordPress install, but you can customise it for any installation by changing the php code within it.)
