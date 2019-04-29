[![Lifecycle: experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental) [![Travis build status](https://travis-ci.com/XiangyunHuang/ElegantBookdown.svg?branch=master)](https://travis-ci.com/XiangyunHuang/ElegantBookdown) [![AppVeyor build status](https://ci.appveyor.com/api/projects/status/github/XiangyunHuang/ElegantBookdown?branch=master&svg=true)](https://ci.appveyor.com/project/XiangyunHuang/ElegantBookdown) [![Launch binder](http://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/XiangyunHuang/ElegantBookdown/master) [![CRAN status](https://www.r-pkg.org/badges/version/placeholder)](https://cran.r-project.org/package=placeholder)

---



### Target

一个 R 包打包了 [ElegantBook 模版](https://github.com/ElegantLaTeX/ElegantBook) 的 bookdown 扩展




### TO DO

- [ ] 制作封面，注意此封面只在生成 PDF 时出现
- [ ] 首先在bookdown下完美复现原 LaTeX 模版的功能
- [ ] 运行跑通 Gitbook/PDF 输出
- [ ] 各个 block 转自定义的 sidebar 借助 Pandoc 和 Lua 实现的 Pandoc filters
- [ ] 各个 block 的 CSS 定制，提示、警告等图标
- [ ] 各个 note warning 块的定制，也是一种 block 可由 Pandoc filters 实现
- [ ] 各种代码块语法高亮的定制和 knitr 提供的语法高亮，最好单独抽出来
- [ ] 基于 Pandoc 提供的 LaTeX 模版还是 rmarkdown 内置的 LaTeX 模版？应该自定义一份极小的补充 ElegantBook 模版的文档
- [ ] 是保持 Pandoc 模版尽量不动，还是保持 ElegantBook 模版不动？
- [ ] 参考 [bookdown-crc](https://github.com/yihui/bookdown-crc) 和 [bookdown-chinese](https://github.com/yihui/bookdown-chinese) 的设计


### 致谢

1. [ElegantBook](https://github.com/ElegantLaTeX/ElegantBook) 开发者
1. [bookdown](https://github.com/rstudio/bookdown) 开发者
1. [Pandoc](https://pandoc.org) 开发者