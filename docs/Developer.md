# Developer

每一个开发者，都应该知道这些。

## 编辑器

### VS Code

插件推荐：

* vscode-icons
* gitlens

## 笔记应用

严谨的开发者会做很好的笔记。

非技术类的笔记，推荐:[极简笔记文件体系](https://www.jianshu.com/p/4da6deb7e9ef)，相应的支持这样无限层级的有 Apple Notes / 有道云笔记/ OneNote等,此外尽管Evernote(印象笔记)依赖于标签(类似博客)管理,其生态以及对于碎片化的知识也值得推荐.

但为开发者定制的偏技术的笔记应用很多无法践行上述原则（比如至少得有代码块、好看）。这里推荐一下它们：

* Boostnote
* Vnote

## FAQ
1. git clone别人的代码后,怎么补充.gitignore放弃的依赖?
    - 在目标文件夹里用`npm install`,自动下载package.json中缺少的依赖