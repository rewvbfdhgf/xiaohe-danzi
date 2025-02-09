# xiaohe-danzi

这个仓库放的是小鹤单字的中州韵（rime）配置文件，官方给出了带词版的rime配置文件，而且码表被锁定了。我喜欢打单字，找了网上的好几个码表，要不就是旧版本的单字码表，小鹤改过一次字频，比如F的一简之前是非，现在是发，对于这种确定性很高的输入方案，改了字序其实影响很大；要么没法修改码表。
我结合了两个码表，搞出了自用的小鹤单字码表，符合现在小鹤飞扬10.10官方版的字序，还可以用快捷键输入标点符号，也可以自己加一些常用的几个词，而且常用的词不限制于4码，比如你可以让巧克力对应qnkeli，这样的好处是你不用专门记多字词，直接用双拼打出来就好，我自己的用法是基本输入单字，再配合零星几个双字词。
因为这个码表中有的字序和小鹤飞扬的有出入，甚至有的字这个码表中居然没有，所以我也在慢慢地修改这个码表中和小鹤飞扬不一致的地方。之后也会将修正后的码表更新。你们在使用中发现了和小鹤飞扬单字模式下输入不一致的地方，欢迎告诉我。

使用方法：把文件复制，粘贴到rime的用户文件夹就好了。
flypy.dict是小鹤的基本码表。flypy_extra是生僻字，很多小鹤飞扬没有的生僻字你都可以照常输入。flypy_full是全码字。flypy_sys是放了标点符号和二重简码，flypy_user是用户码表，你可以自定义你的词库，不局限于四码。基本上你要动的也就是flypy_user了。对了我不习惯四码上屏，都是敲空格上屏，这样也方便输入大于4个字母的单词，就不用按shift切换，输入完后再切换回来，如果你不习惯，可以在flypy.schema里面修改。

网上的两个码表来源：
1 https://github.com/OscarXWei/hesingle
2 https://github.com/cubercsl/rime-flypy
  https://github.com/jqtmviyu/flypy
