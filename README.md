#vimtones 说明
----
## 介绍
- 作者只会写OSＸ平台，也就是此插件只支持 **MacVim**，非OS X平台请各路大神自己搞
- 这个插件的作用是
  * 给 Vim 添加按键音
  * 让系统音量随 Vim 的键入速度实时调整

## 安装方法
- 把 `plugin` 文件夹中的 `vimtones.vim` 复制到系统目录 `~/.vim/plugin` 中
- 吧 `vimtones` 文件夹复制到 `~/.vim` 目录下

## 配置
- 需要给 `vimrc` 添加如下几行


		let g:vimtonesTurnOn = 1
		let g:vimtonesPlaySound = 1
		let g:vimtonesChangeVol = 1
		let g:lastinputTime = str2float(reltimestr(reltime()))
	
- vimtonesTurnOn：插件整体开关
- vimtonesPlaySound：是否播放按键音
- vimtonesChangeVol：是否实时调整系统音量

## 其他
- `vimtones/mp3` 中内置了老式打字机的声音和一些钢琴音，只需把选择的按键音重命名为 `key.mp3` 即可
- 此插件可自由修改传播，但请注明原作者 ds303077135@Gmail.com
- 折腾愉快！
