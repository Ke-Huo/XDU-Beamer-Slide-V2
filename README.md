# XDU-Beamer-Slide-V2
西电beamer模板

根据大连理工模板修改而来，**[源链接](https://github.com/fuujiro/DLUT-Beamer-Slide-V2)**

## 文档目录与编译方式

`TexLive 2020`完整编译方式为`xelatex slide`→ `bibtex  slide`→`xelatex slide`*2

或直接运行根目录下的`make.bat`

```bash
│  make.bat                   #编译脚本
│  README.md                  #自述文件
│  ref.bib                    #参考文献
│  slide.pdf                  #生成的beamer
│  slide.tex                  #beamer主文件
│  slide.vrb                  #中间文件(不用管)
│  XDU.sty                    #样式
│  
└─pic                         #图片文件夹
        dtmf.pdf
        logo-blue.pdf
        logo-red.pdf
        SEE.pdf
```

