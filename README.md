Extends default MVW theme to render LaTeX using the MathJax [CDN][1].  Serves as an example of using custom themes and python markdown extensions in MVW.

Include `theme: mathjax` at the beginning of your file to enable MathJax rendering. LaTeX can be included inline between single dollar signs or in blocks between double dollar signs.

Clone the repository and run `mvw` from the top directory to see demo.  See `.mvw/config.yaml`, `.mvw/theme/extensions/mdx_mathjax.py` and `.mvw/theme/template/mathjax.html` for configuration of extension.

[1]: http://www.mathjax.org/download/mathjax-cdn-terms-of-service/
