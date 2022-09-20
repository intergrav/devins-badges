## ❓ About
This is Devin's Badges! A project I work on in my spare time that contains cool badges for you to use in your projects.

I aim to be as consistent as possible with these. I also try to make these look great on most modern sites.

## 📰 Using in your project
Adding these badges to your website? Follow these steps! You can use the `svg` files instead of `png` if you would like, however, you will have to change the height so it looks nice.

All you really need to do is copy one of these code blocks depending on what file type and badge type you are using this with, and do all of these.
- Replace `~category~` with the folder your badge is in.
- Replace `~badge~` with the name of the badge.
- Replace `~link~` with whatever you are linking to.
- Replace `~alttext~` with you guessed it - alt text.

Check out the [assets](https://github.com/intergrav/devins-badges/tree/v2/assets) folder to see all the badge types. I don't have a website for badge picking currently, but that might come in the future if anyone wants to make one.

I highly recommend using HTML when possible as you can't resize the badges with Markdown.

### HTML

> #### Cozy (biggest) (recommended height 48-64)
> ```html
> <a href="~link~"><img src="https://raw.githubusercontent.com/intergrav/devins-badges/v2/assets/cozy/~category~/~badge~_64h.png" alt="~alttext~" height="50"></a>
> ```

> #### Compact (less tall, wider) (recommended height 34-46)
> ```html
> <a href="~link~"><img src="https://raw.githubusercontent.com/intergrav/devins-badges/v2/assets/compact/~category~/~badge~_46h.png" alt="~alttext~" height="36"></a>
> ```

> #### Minimal (icon only) (recommended height 48-64)
> ```html
> <a href="~link~"><img src="https://raw.githubusercontent.com/intergrav/devins-badges/v2/assets/minimal/~category~/~badge~_64h.png" alt="~alttext~" height="50"></a>
> ```

### Markdown
#### ❗ Use HTML when possible, as you can't change the height through Markdown.

> #### Cozy (biggest)
> ```markdown
> [![~alttext~](https://raw.githubusercontent.com/intergrav/devins-badges/v2/assets/cozy/~category~/~badge~_64h.png)](~link~)
> ```

> #### Compact (less tall, wider)
> ```markdown
> [![~alttext~](https://raw.githubusercontent.com/intergrav/devins-badges/v2/assets/compact/~category~/~badge~_46h.png)](~link~)
> ```

> #### Minimal (icon only)
> ```markdown
> [![~alttext~](https://raw.githubusercontent.com/intergrav/devins-badges/v2/assets/minimal/~category~/~badge~_64h.png)](~link~)
> ```

Also, you don't need to add credit - it would be nice for you to do so, but I really don't care if you do or not. I just make these for fun!

## 📄 Some guidelines I recommend following

While you don't have to do this, I recommend following these guidelines to make sure the badges look great on your page.
- Don't modify the badges unless needed
- Don't have the badges too close to other text

## ➕ Adding more badges
Want to add your own badges to the project? Feel free to open up an issue and I'll make one! This project is made with Figma. If you are opening a PR, I will probably edit your badge just to make sure it fits in as well as possible with the rest.

## ⭐ Enjoy this project?
Please star this GitHub repository if you enjoy this project!

## ❗ Disclaimer!
This is currently a work in progress, I only have a few badges for a few services right now. However, I am planning to have a lot more badges in the coming weeks.

<script src="https://giscus.app/client.js"
        data-repo="intergrav/devins-badges"
        data-repo-id="R_kgDOH_9quQ"
        data-category="giscus"
        data-category-id="DIC_kwDOH_9quc4CRdU3"
        data-mapping="pathname"
        data-strict="0"
        data-reactions-enabled="1"
        data-emit-metadata="0"
        data-input-position="top"
        data-theme="transparent_dark"
        data-lang="en"
        data-loading="lazy"
        crossorigin="anonymous"
        async>
</script>