# Seldom

A minimal [Ghost](https://ghost.org) theme.

## Installation

Move the `seldom` folder into `content/themes` in your Ghost installation. Restart Ghost and select Seldom in your Ghost settings.

## Options

### Post Excerpts

`index.hbs` and `tag.hbs` can be modified to show post excerpts instead of full posts. Change `"post-full"` to `"post-excerpt"`. The length of the excerpt can be modified in `partials/post-excerpt.hbs`. The default length is 30 words.

### YouTube Embeds

To embed a YouTube video that scales to fit the width of a post, put the embed code inside a `.yt-wrapper` and remove any hard-coded dimension attributes. For example:

```
<div class="yt-wrapper">
    <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allow="encrypted-media" allowfullscreen></iframe>
</div>
```

## Copyright

Copyright (c) 2020 Martin Gordon

Released under the MIT License.

Portions of code were borrowed from:

- [Arabica](https://github.com/slunsford/arabica), copyright (c) 2014-2018 Sean Lunsford. Used under MIT License.
- [Casper](https://github.com/TryGhost/Casper), copyright (c) 2013-2014 Ghost Foundation. Used under the MIT License.
