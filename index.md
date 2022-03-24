## Some Thoughts

### 24-Mar-2022
2
​
While reviewing some Vue.. Just discovered [Svelte ] through Modzilla suberb as usual []
3

I couldn't resist joining others' enthousiams for this JS library.

Over the past few years (almost 10 actually, jee time flies), I have been using React, Angular (2+) and more recently Vue in different settings. All are Ok to work with​. I liked the flexibiloty of React, using JS to build  (I was coming from server templates and disliaked temaplrte for this reason. But I disliked the compelxity of the cde that could result of the lack of opinioanticity. Angular brought some kind of organization by default but ended up being heavy in number of liness and only MS guys really liked it. Vue was a good compromise, with a lot of the issues found with React or Angular addressed upfront. But it's syntax was stillhevier than necessary. Why? Mainly because of the model followed by all these platform , which was to interactivey update the DOM at runtime.
Then came Sveltwe. Waht you see first i s"Compilation" That sond frightening, remining the old times befre IDE even existed. But then you realize that all these framework actually use compilation (even theoritcally it wouldnt be necessary) because you want to have integration in your development environement, You want to see your change right away, whenever you want, from you IDE to your browser. So Svelte do the same but, at the same time, produce drectely executable JS. The result is lighter, faster to load, better responding code.
More importantly, it allows ligher code as you dont need to rely on the intrinsic structure of JS classes to discribe your component. you dont need to describe the state as a funciton or whatever. In Svelte, everything is a component and a component is just a file containing simple JS, some HTML template and CDD style if needed. Because it's then compiled to build your application as complex as it can be, it's closer to simple JS and that's a charm. State can be any of your "global" variable in your component. The copiler will know that, if they are assigned and reference elsewhere, they will need to become reactive. And it goes on and on. The team implemented all kind of shortcuts and simplications, possible because of the compilation step was embraced upfront (there is some kind of complation with other framewrks; Svelte simply decided to embrac it by design, and that makes all the difference).

[Edit](https://github.com/Jean-Maupas/Blog/edit/gh-pages/index.md)
[Markdown](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).
30
