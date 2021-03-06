osu! Program Files - Chinese
===============================

![osu! Program Files in nutshell](Osu!sys.jpg "osu! Program Files in nutshell")

位置
-----

### Windows

| 现版本默认路径 | 旧的安装程序路径 |
| ------------------------ | ---------------------- |
| C:\Users\<Username>\AppData\Local\osu! | 	C:\Program Files\osu! / C:\Program Files(x86)\osu! (for 7 64-bit or 8) |
> "C:" 你安装osu! 的硬盘.

文件夹
------

### \_MACOSX

**osu! for Macintosh OS.** 对于windows用户，你可以删除这个文件夹。

### Chat

只有当你曾经在对话框中使用 */savelog* 指令或你启用了 *自动记录私人消息* 功能时才会出现.记录了你在osu! 内对话标签的内容.

文件以 `{Tab_name}-{YYYYMMDD}-{HHMMSS}.txt`的形式保存, 可以以任何文本编辑器打开(Notepad).
**实例:** #multiplayer-20121115-040845 (/savelog at #multiplayer tab in 15th November 2012 at 0408hrs and 45secs).

### Downloads

当你使用 *osu!direct* 功能后会出现.**保存你通过 osu!direct 正在下载的.osz文件**,完成下载后会作为合法的beatmap被转移到osu! 下的Songs文件夹.

### Exports

当你使用 [Skin Selector's "导出.osk"](/wiki/Options) or [Beatmap Editor's "导出包"后出现](/wiki/Beatmap_Editor/Menu).**保存你从osu! 导出的.osz(beatmap)/.osk(皮肤)文件.**[For how-to, click me](/wiki/osu!_File_Formats).

### Localisation

当你在选项页切换语言时出现.**保存可以替换英文文本内容的你所选择的语言的文本**.

### Replays

保存**可执行的osu! replay文件(.osr)**.如果与rep对应的beatmap不存在,osr文件将无法工作.osr文件保存了游戏结果数据和光标移动轨迹.你可以在结果页面按下**F2**或在在线排名页面(只有在solo下出现,在结果页面下面)点击 **Save as .osr**来创建.osr文件.不保存多人游戏结果..osr的文件大小在100kb-1kb不等.[想要上传rep到youtube的玩家可以参考本页面](https://osu.ppy.sh/forum/t/108092)

格式为 `{Local player name} - {Artist} - {Title} {[Difficulty]}{(YYYY-MM-DD)} {Game Mode}`
**Example:** dummytest1 - Loituma - Ievan Polkka [SPINNER-MADNESS]  (2013-08-12) OsuMania

### Screenshots

*保存osu! 的截图(默认为F12)*. 截图格式(.jpg/.png)取决于你在选项中设置的结果.

格式为 `screenshot###` *###* 表示你的截图数量.

### Skins

保存了用户自定义的皮肤,这些皮肤可以改变osu!的视觉表现.你可以在皮肤标签下使用osume!.exe(osu! 升级器)来获取更多皮肤,你也可以登录[论坛](https://osu.ppy.sh/forum/15)获取皮肤.从osume!.exe 获取的皮肤将被立即读取并可以使用.如果你是从论坛获取的皮肤,有两种情况.如果皮肤是.osk形式的,你可以直接打开该文件,osu!将被启动并导向皮肤选择页面,你的新皮肤将被添加进列表里.如果皮肤是文件夹形式的,你必须将新皮肤的文件夹手动拖入该目录.如果皮肤是.zip/.rar格式的,你必须先解压,再按照文件夹的形式操作.你可以在[Options menu under Skins tab (Skin Selector)中更改你的皮肤](/wiki/Options).请记住皮肤*只在你自己的osu! 程序中生效*.

关于皮肤的更多信息,请参考[Skining页面](/wiki/Skinning).*osu! by peppy* 是惟一一个不在该目录下且不能被直接删除的皮肤.

### Songs

**保存osu! beatmaps实际文件的位置**. 通常包含 .osu (不同难度), .mp3/.ogg (音乐文件), .jpg/.png/.gif (背景文件), .osb (StoryBoard文件) 和 .mp4/.flv (视频文件). 可能包含 .wav/.ogg (打击音效文件) 和 目录 (SB spites 和/或 皮肤).

命名形式为 `{Beatmap 编号} {艺术家} - {标题}`.
**Example:** [57950 SOUND HOLIC - Drive My Life](https://osu.ppy.sh/s/57950)

请注意'在osu! 初期的'陈旧的*beatmap*不包含序号且不遵循以上命名规律.可以参考范例"[discoprince](http://osu.ppy.sh/s/1)" 或 "[avgn](http://osu.ppy.sh/s/66)".特别需要注意的是"[tutorial](http://osu.ppy.sh/s/3756)",因为每个通过osu! installer安装的玩家都会拥有该beatmap.并且,人工创建/废弃 的 .osz/.zip 歌曲目录同样会进行计数(?需要修改).

### 隐藏文件夹

#### Data

**osu!data files.** 不要修改这个文件.

Program files
---------------

### .db (数据库文件)

.db文件保存了beatmap信息,这些文件只能由osu!.exe/osu!test.exe使用.Notepad可以打开这类文件但通常你只会得到大量加密的字符串.

**osu! 数据库**

-   collection.db (你在游戏中的收藏夹.你可以把这个文件上传到论坛以便他人查看你的收藏.实际的beatmap不包含在内.)
-   osu!.db (osu! beatmap缓存.)
-   presence.db (在对话页面的玩家信息缓存.)
-   scores.db (保存本地历史成绩)

### .cfg (配置文件)

配置文件确认了osu! 的初始设定,这些文件可以通过Notepad打开.

-   osu!.cfg (osu! 逻辑配置.)
-   osu!.{YOUR PC NAME}.cfg ("[Options](/wiki/Options) screen". Also contains [deprecated/interesting variables and sensitive information](/wiki/User_configuration_file))
    -   {YOUR PC NAME}: 你的计算机用户名. 如果你将admin/user的用户名设置为 "HelloWorld", .cfg 文件将被命名为, osu!.HelloWorld.cfg .

### .exe (应用程序)

主要部件.点击后可以启动.如果你使用osu!installer安装osu!,那么这些.exe文件是安全的.

-  osu!.exe (启动osu!)

### 隐藏文件

#### .dll (应用程序拓展)

.dll文件是osu!.exe程序的组成部件,请忽略该类文件.

**基础部件** (For Microsoft .NET)

-   avcodec-51.dll
-   avformat-52.dll
-   avutil-49.dll
-   bass.dll
-   bass_fx.dll
-   d3dx9_31.dll
-   Microsoft.Ink.dll
-   Microsoft.Xna.Framework.dll
-   pthreadGC2.dll
-   x3daudio1_1.dll

**osu! 程序部件**

-   osu!gameplay.dll
-   osu!ui.dll
-   osu.dll
