# CSL-Chinese-IR-CSSCI-Journals
中文国关及小部分综合社科期刊CSL

基于fazhen的《历史研究》以及pulipuli的中文APA格式改进制作

**详细改进：**

1. 作者之间的连接符，中文为“、”，英文为“,”和“and”
2. 英文的页码，单页码为 p. 多页码为 pp.
3. 英文的编者以及译者，单人为 ed. 和 tran. 多人为 eds. 和 trans.
4. 按期刊要求，网页需要标注日期的话，目前英文网页的日期也顺利转为中文日期格式 
5. 增加“同上”以及“Ibid.”中英同文献引用
6. 在Word插件中顺利实现插入引用页码
7. 《国际安全研究》、《国际政治研究》、《太平洋学报》、《现代国际关系》四本期刊使用“存档位置”域作为中文译著的作者国籍
8. 条目类型为书籍、作者为编者，也就是没有采用“章节”条目类型的情况下，也能直接输出编者

**特性：**

1. 仅支持中文，英文，日语、韩语等小语种尚未支持
2. 由于学科特性，文末参考文献格式同文中引用格式
3. 除《现代国际关系》，期刊均直接标注全页码、编著章节标注章节全页码
4. 页码连接符为en dash
5. 仅支持 期刊、著作、编著、报纸、学位论文、网页
6. 似乎没有找到更多有关于书籍版本的参考，因此格式里默认没有添加版本信息
7. 学位论文挺少引用的，基本按照书籍的格式来做
8. 网页格式除非看到要写访问时间，否则我都没添加，以作者为先，标题在中，跟着是网站标题、日期、网址
9. 有些期刊需要作者国籍，这个就真没办法了，我用的zotero没有这个选项，变通的办法就是用word插件中的前缀添加
10. 有的期刊，外文著作（中译本）作者后要添加“著”，中国作者倒不用，这个也是CSL没法解决的
11. 网络上的档案、公开报告、博客等等，还请归类为网页，也是个变通的法子
12. **存在的问题：《现代国际关系》的期刊引用中文文献的页码连接符是“~”，没有添加，仍是默认的en dash**
13. **《历史研究》的英文文献，如果不指定引用页码，会以“.”收尾、中文文献没有，其他期刊的中英文均无句号收尾，请自行添加后缀解决**
