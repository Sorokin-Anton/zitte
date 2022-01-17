---
page:
  headHtml: |
    <link href="https://cdn.jsdelivr.net/npm/prismjs@1.23.0/themes/prism-tomorrow.css" rel="stylesheet" />
    <script src="https://cdn.jsdelivr.net/combine/npm/prismjs@1.23.0/prism.min.js,npm/prismjs@1.23.0/plugins/autoloader/prism-autoloader.min.js"></script>
    <script>
      window.MathJax = {
        startup: {
          ready: () => {
            MathJax.startup.defaultReady();
          }
        }
      };
    </script>
    <script async="" id="MathJax-script" src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

template:
  theme: green
  # name: /templates/layouts/note
  sidebar:
    collapsed: false
  urlStrategy: pretty

pandoc:
  rewriteClass:
    red: text-red-700 font-bold text-3xl

---



# Anton Sorokin's webpage

Currently nothing interesting here. Created via [Emanote]. Some code: `aaaa+2^2`
```haskell
import Control.DeepSeq (force)
import Control.Exception
import Data.HashMap.Lazy (HashMap)

main = undefined
```

Some math: inline as $2+2^2$ and display as:
$$
\frac{1412334^3}{2}
$$

TODO:
aasd

sdf

<iframe  src="https://www.youtube.com/embed/ppC0IFbde1Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

[ ] aaa
- [x] bbb
- [ ] ccc
- [ ]
  - [x] DD
  - [ ] E

See [[READzME|this]] [plz]{.red}

[Emanote]:https://emanote.srid.ca/
