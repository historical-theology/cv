# Dr. Corey Stephan's LaTeX Academic CV
## Public Template Version
*with all contact and reference information redacted*

I have customized my LaTeX academic CV from [Dr. Bastian Rieck's LaTeX academic CV template](https://github.com/Pseudomanifold/latex-cv), which is, in turn, based on [Dr. Dario Taraborelli's](http://nitens.org/taraborelli/cvtex).

I release this code under the same license as Dr. Rieck, that is, the MIT License.

## Major Customizations

1. Compilable in TeXLive by default

Dr. Bastian Rieck's original, beautiful LaTeX CV template requires multiple external fonts to be installed and the use of the fontspec package (which only works in LuaLaTeX) to load them. 

I intend for my own CV, however, to be compilable with any full TeXLive installation (on a *BSD or GNU/Linux operating system) via either LuaLaTeX or XeLaTeX as-is. 

Hence, for example, I strictly use the old-style and proportional variant of Dr. Edward Tufte's book font, [ET Book](https://edwardtufte.github.io/et-book/), which is included in TeXLive within the {ETbb} package. (This also happens to be my longtime favorite font.)

2. Overall closer alignment with Dr. Karen Kelsky’s [Rules of the Academic CV](https://theprofessorisin.com/2016/08/19/dr-karens-rules-of-the-academic-cv/), as well as the expected norms for curricula vitae in the fields of history and theology

3. Denial of *all* orphaned and widowed lines with the (admittedly draconian) command `\usepackage[defaultlines=100,all]{nowidow}`

4. Overhauled header, including automatic dating for the document with `\usepackage[useregional]{datetime2}` in the preamble and, subsequently, the `\today` command in the header itself
