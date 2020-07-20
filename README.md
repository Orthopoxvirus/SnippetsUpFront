# SnippetsUpFront
1. Add some text snippets you want to use in product descriptions or product meta descriptions here: your-shop.com/admin#/sw/settings/snippet/index
1. Use those text snippets by adding a twig templating block into the description container {{ 'path.of.your.text.snippet' | trans | raw }}. You may use HTML in your snippets. Just don't forget to add the | raw filter.
