# Hello, World!

<!-- Unfortunately I can't find a better way than this to vertically align two images with GitHub markdown -->
<table><tr><td valign="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=MysteryBlokHed&theme=dracula&include_all_commits=true)

</td><td valign="center">

![Most Used Languages](https://github-readme-stats.vercel.app/api/top-langs?username=MysteryBlokHed&theme=dracula&layout=compact)

</td></tr></table>

## About my projects

### [Cluecards](https://github.com/MysteryBlokHed/cluecards)

At first I thought this project was actually going to be relatively simple to implement,
but it actually ended up being quite challenging and fun to do.
The difficulty here was actually in the discovery of inference methods much more than the code implementation of them.

This was my first time learing and applying set theory, although it wasn't actually until
after I had started work on the inference logic that I realized that.
Speaking of: I've also tried to document the theory/proof behind what my code does on
[a page in that repo](https://github.com/MysteryBlokHed/cluecards/blob/main/Inference.md).
Hopefully it's as interesting to read as it was to write.

I also decided to eventually port the core of the inference logic to Rust (with WebAssembly),
because I noticed performance issues for a feature to determine the most likely guilty cards
(since it's essentially just brute-forcing all possible hand arrangements given the current data).
That was my first time ever using WebAssembly.

## My contributions

### [color.js](https://github.com/color-js/color.js)

I've been invited to help maintain this project, along with a handful of some other great developers: <https://github.com/orgs/color-js/people>.
Most of my work here is on writing and updating typings for TypeScript support.
