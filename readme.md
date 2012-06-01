# Solid

打算在nodejs上开发一个类似于[jekyll](https://github.com/mojombo/jekyll)的静态blod生成工具。
主体功能相当于jekyll的移植，jekyll依赖的ruby库去找nodejs对应的版本。

jekyll貌似每次都会把所有文件转换，如果文件太多了可以考虑像make工具一样通过时间戳来转换新建或修改过的文件 。

这样就需要对文件名、category、tag数据进行索引和存放。这些都是jekyll没有的功能。

同时，考虑通过ftp将博客自动部署到空间，部署工具也应该只部署新建或修改的文件。