## Some Thoughts

### 24-Mar-2022

While reviewing some documentation for a Vue project, I discovered [Svelte](https://svelte.dev/) through [Modzilla](https://developer.mozilla.org/en-US/docs/Web) suberb [documentation](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks)

I couldn't resist joining others' enthusiasm for this JS library.

Over the past few years (almost 10 actually, jee time flies), I have been using React, Angular (2+), and more recently Vue in different settings. All are Ok to work with. I liked the flexibility of React, using JS to build  (I was coming from server templates and disliked templates for this reason. But I disliked the complexity of the code that could result from the lack of opinion. Angular brought some kind of organization by default but ended up in a large number of lines that only MS guys would really like. Vue was a good compromise, with a lot of the issues found with React or Angular addressed upfront. But its syntax was still heavier than necessary. Why? Mainly because of the model followed by all these platforms, which was to interactively update the DOM at runtime.

Then came Sveltwe. What you see first is"Compilation" That sounds frightening, a reminder of the old times before IDE even existed. But then you realize that all these frameworks use compilation (even theoretically it wouldn't be necessary) because you want to have integration in your development environment, You want to see your change right away, whenever you want, from your IDE to your browser. So Svelte does the same but, at the same time, produces directly executable JS. The result is lighter, faster to load, better-responding code.

More importantly, it allows lighter code as you don't need to rely on the intrinsic structure of JS classes to describe your component. you don't need to describe the state as a function or whatever. In Svelte, everything is a component and a component is just a file containing simple JS, some HTML template, and CDD style if needed. Because it's then compiled to build your application as complex as it can be, it's closer to simple JS and that's a charm. A state can be any of your "global" variables in your component. The compiler will know that, if they are assigned and referenced elsewhere, they will need to become reactive. And it goes on and on. The team implemented all kinds of shortcuts and simplifications, possibly because the compilation step was embraced upfron

[Edit](https://github.com/Jean-Maupas/Blog/edit/gh-pages/index.md)
[Markdown](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

