## Documentation

Presentation on MapActions project with Insecurity Insight.

### Git Submodules

Rather than having a whole [RevealJs](https://github.com/hakimel/reveal.js/) library within this repo & to avoid ambiguity around source of the core functionality of this presentation, I've made use of Git submodules as outlined in this [blog post](https://medium.com/@martinomensio/how-to-host-reveal-js-slides-on-github-pages-and-have-a-tidy-repository-1a363944c38d).

```
git submodule add https://github.com/hakimel/reveal.js.git
```

### Developing

```
yarn && yarn dev
```

### Deploying

This presentation is deployed on [Netlify](https://www.netlify.com/), so just push changes to github & it will automatically deploy [here](https://presentation-microfrontends-a-journey.netlify.app).
