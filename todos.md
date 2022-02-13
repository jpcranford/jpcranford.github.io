Grouped roughly from less to more difficult:

- [x] Remove share links from post
- [ ] Figure out MuseScore profile links
- [ ] Figure out PayPal donation link
- [ ] Figure out what I'm gonna do for the footer links
    - Remove links to About page?
    - If keep, definitely redesign logos to be less google android-esque
- [ ] Write About page
- [ ] Customize theme
    - [ ] Get site icon centered over name
    - From Carte Noire - Github [repo](https://github.com/jacobtomlinson/carte-noire), [demo site](http://carte-noire.jacobtomlinson.co.uk)
        - [ ] Dark mode colors
        - [ ] Sidebar navigation and profile icons
        - [ ] Also link color change on hover
        - Font too big on posts
        - Maybe: big icon above site name = FontAwesome's `piano-keyboard`?
    - Possible dark mode colors from [5eTools](https://5e.tools/index.html)'s alt night mode
- [ ] Customize CSS for GitHub gist embeds so they're not so ugly
- [ ] Customize CSS for GitHub gist embeds so they're not so long
    - Possible [help](https://betterstack.dev/blog/how-to-embed-a-github-gist-in-your-website/)
- [ ] Add copyright section - "Unless otherwise noted, and to the extent available to the author, this website and its contents are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>."
    ```html
    <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
    ```
- [ ] Get page's published date from front matter, rather than filename.

### Notes
- MuseScore embeds &mdash; that is, the `iframe`'s `height` property &mdash; should be set to **600** for shorter embeds, or **1100** for full-page ones. (aka 100 pixels per inch)
