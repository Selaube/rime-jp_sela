日文输入，假名+汉字
- 片假名编码大写，小号假名前加x/X。例「あ - a」「ア - A」「ぁ - xa」「ァ - XA」
- 汉字编码都是小写罗马音，前面加q。例「会 - qa」「白上 - qshiraqkami」。dict里只有单字，不过rime里输入过一次的词都会自动录入用户数据
- 汉字来自[文化厅 - 常用汉字表](http://www.bunka.go.jp/kokugo_nihongo/sisaku/joho/joho/kakuki/14/tosin02/index.html)，去掉了括号内的字，如「悪(惡)」-「悪」
- 因为上一条的原因，某些字没有，如「俺」，还有字的特殊读法像「圆 - madoka」也没有
- 假名来自[平文式罗马字 - 维基百科](https://zh.wikipedia.org/wiki/%E5%B9%B3%E6%96%87%E5%BC%8F%E7%BD%97%E9%A9%AC%E5%AD%97)，有修改，如「じ ジ ji，ぢ ヂ ji」-「じ ジ ji，ぢ ヂ di」、「ず ズ zu，づ ヅ zu」-「ず ズ zu，づ ヅ dsu」
- 特殊字符：「- ：ー」「々ゝゞ	ヽヾ	〃	：onaji」，「」『』是rime自带的，[]、shift+[]
- 输入法的使用和设置参见[Home · rime/home Wiki](https://github.com/rime/home/wiki)

其他：
- 作者是日文丈育，做完也没有测试，主要是自用
- 「其他数据.zip」里是制作中产生的文件，包括pandas处理xls的程序、制作记录log.txt、汉字表
- 小写假名和片假名的输入方式参考了[lotem/rime-kana: 日文假名 Rime 輸入方案](https://github.com/lotem/rime-kana)
