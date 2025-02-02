+++
date = '2025-01-04T10:14:11+02:00'
draft = false
title = 'Hello, World!'
summary = "The first content"
tags = ['学习', '日常']
+++

The first content

<!--more-->

# First & Test Page

> 日々私たちが過ごしている日常は、実は、奇跡の連続なのかもしれない  
> 我们所经历的每个平凡的日常，也许就是连续发生的奇迹。

## Nim

```nim
echo "Hello, World!"
```

## Go

```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```

## Python

```python
import os
import subprocess

# 获取文件夹路径
folder_path = "Your Path"
# 遍历文件夹中的所有文件
for root, dirs, files in os.walk(folder_path):
    for file in files:
        # 检查文件名后缀是否为mp4或m4a
        if file.endswith(".mp4"):
            mp4_path = os.path.join(root, file)
            m4a_path = os.path.join(root, file.replace(".mp4", ".m4a"))
            output_path = os.path.join(root, file.replace(".mp4", "_merged.mp4"))
            
            # 使用ffmpeg合并mp4和m4a文件
            subprocess.run(["ffmpeg", "-i", mp4_path, "-i", m4a_path, "-c", "copy", output_path])
```

## CJK

### GB2312(节选)

℃ ＄ ¤ ￠ ￡ ‰ § № ★ ⒛ ⑴ ＊ ＋ ， － ． ／ ０ お く ぐ け げ こト ド ナ ニ ヌ ネ ノ ハ バ パ ︵ ︶ ︹ ︺ ︿ ﹀ И Й К Л М Н ㄒ ㄙ ㄚ ㄛ ┚ ┛ ├ 卮 氐 囟 胤 馗 毓 睾 鼗 亟 僖 儆 僭 僬 僦 苻 苓 茑 茚 茆 茔 茕 掼 揲 揸 揠 揿 揄 揞 揎 唣 猬 猸 猱 獐 獍 獗 獠 獬 阋 阚 滏 潆 潇 漤 漕 邂 邈 邃 驺 驿 驽 缫 缬 缭 缯 缰 缱 缲 韬 橐 樽 樨 橘 罹 羁 罾 盍 褶 襁 蝾 蝻 箴 篑 篁 篌 篥 綦 綮 繇 纛 蹑 蹒 蹼 蹯 蹴 躅 饔 髻 髭 髹

### GBK(节选)

〇 〡 〢 〣 〤 〥 〦 〧 〨 〩 ㊣ ㎎ ㎏ ㎜ ㎝ ㎞ ㎡ ﹗ ﹞ ﹟ ﹠ ﹡ ˙ ― ℅ ℉ ↙∕ ∟ ∣ ╬ ╭ ╯ ╱ ╲ ╳ ▁ ▂ ▃ ▄▕ ▼ ╜ ╫ 丏 丒 丗 丟 丠 両 丣 喩 喪 喫 喬 喭 單 喯 尷 屃 屄 屆 屇 屌 屍 屒 屓 屔 屖 屗 屘 撘 撚 撛 撜 撝 撟 撠 撡 撢 撣 撥 撦 撧 撨 柪 柫 柭 柮 柲 柵 柶 柷 柸 柹 柺 査 柼 柾 栁 栂 爯 爲 榓 榖 榗 榙 榚 榝 榞 榟 榠 榡 榢 榣 榤 榥 榦 暊 暋 暍 暎 暏 暐 暒 暓 暔 暕 暘 暙 暚 暛 暜 暞

### GB18030-2000(节选)

Ä Æ Å À Á Â Ã Ç È É Ê Ë Ð Ì Í Î Ï Ö Ø Ò Ó Ô Õ Ñ Ù Ú Û Ü Ý Þ ä æ å â ã ç ë ð î ï ö ø ô õ ñ û ý þ 㑇 㑊 㕮 㘎 㙍 㙘 㙦 㛃 㛚 㛹 㟃 㠇 㠓 㤘 㥄 㧐 㧑 㧟 㫰 㬊 㬎 㬚 㭎 㭕 㮾 㰀 㳇 㳘 㳚 㴔 㵐 㶲 㸆 㸌 㺄 㻬 㽏 㿠 䁖 䂮 䃅 䃎 䅟 䌹 䎃 䎖 䏝 䏡 䏲 䐃 䓖 䓛 䓨 䓫 䓬 䗖 䗛 䗪 䗴 䜣 䝙 䢺 䢼 䣘 䥽 䦃 䲟 䲠 䲢 䴓 䴔 䴕 䴖 䴗 䴘 䴙 䶮

### 附. CJK(节选)

扩展 A 区: 㑇 㑊 㘎 㙍 㙘 㛃 㛹 㠇 㠓 㧐 㧑 㬊

扩展 B 区: 𠅤 𠙶 𡎚 𡐓 𣗋 𣲗 𣸣 𤩽 𤫉 𥖨 𦈡 𦒍

2005 新增: 龦 龩 龪 龭 龰 龱 龴 龵 龷 龸 龺 龻

扩展 C 区: 𪟝 𪣻 𪨰 𪨶 𪩘 𫄧 𫇭 𫌀 𫍣 𫍲 𫍽 𫐐

扩展 D 区: 𫞩 𫟅 𫟦 𫟹 𫟼 𫝀 𫝁 𫝃 𫝄 𫝅 𫝆 𫝇

扩展 E 区: 𫢸 𫫇 𫭟 𫭢 𫭼 𫮃 𫰛 𫵷 𫶇 𫷷 𫸩 𬀩

急用汉字: 鿍 鿎 鿏 䲤 鿑 鿒 鿓 鿔 鿕

扩展 F 区: 𮧵 𮀔 𬺰 𬺱 𬺲 𬺳 𬺴 𬺵 𬺶 𬺷 𬺸 𬺹

2017 新增: 鿥 鿦 鿧 鿨 鿩 鿪 鿖 鿗 鿙 鿚 鿜 鿠

2018 新增: 鿫 鿬 鿭 鿮 鿯

扩展 G 区: 𰻝 𰻞 𱁬 𰜩 𰀴 𰅐 𰆀 𰈀 𰊐 𰊠 𰍠 𰔀

急用科学与技术用字: 鿰 鿱 鿲 鿳 鿴 鿵 鿶 鿷 鿸 鿹 鿺 鿻 鿼

需分离的汉字: 䶶 䶷 䶸 䶹 䶺 䶻 䶼 䶽 䶾 䶿

昆曲工尺谱用字: 𪛗 𪛘 𪛙 𪛚 𪛛 𪛜 𪛝

扩展 H 区: 𱍐 𱍧 𱎺 𱏫 𱐝 𱚋 𱣋 𱩁 𱰜 𱹫 𲁩 𲎯

扩展 I 区: 𮯰 𮱅 𮱸 𮲫 𮳞 𮴆 𮴼 𮵮 𮶖 𮷊 𮸌 𮹝