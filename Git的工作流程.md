Git的工作流程
1、如何将本地的更改与仓库进行联系
2、如何将仓库的更改与本地进行联系

如何将本地的更改与仓库进行联系
①在本地找到与仓库对应的文件夹，在文件夹中选定需要更改改文档进行编辑；
②更改完成后，选定文件夹，点击右键，打开Git GUI Here，可以看到在左上角的框框中有所需的文档，点击Stage Changed，文档将转移至左下角的暂存区中，而后点击
sign off后可在右下框中为文档进行标记；
③标记后，点击commit后，再点击push，然后会出来一个新的页面，再次点击push，等待文档传输，显示成功后，即可关闭；
④完成以上步骤后，刷新githup的页面，就可以看到更改后的文档啦。

如何将仓库的更改与本地进行联系
①在githup中找到仓库；
②对仓库中需更改的文档进行更正，更改后回到仓库页面，点击绿色按钮Clone or download，复制网址；
③在本地文件中找到与githup中对应的文件夹，点击右键，打开Git Bash Here，在$后空格输入git clone，在后面空格后，点击右键后点击Paste将之前复制的网址进行粘贴，点击回车后即可；
④点击查看文档，就可以看到更改后的文档。
