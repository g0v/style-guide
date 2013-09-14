# Coding Style
# File Organization
# Naming Convention
# Shadow/陰影
先回憶一下 box-shadow 怎麼設吧 http://www.w3schools.com/cssref/css3_pr_box-shadow.asp
>	box-shadow: x y blur spred color inset

我們將陰影大致分為以下四種：

1. <div style="box-shadow: 0 0 1px 1px #999; width: 4em;"><br /><br /></div>
給人簡潔的感覺，blur 設在 1-3px 都可以給人這種感覺。此時 spred 相當於 border 的作用，而相較於單純使用 border 時 blur 多提供了一點點漸層的感覺。
2. <div style="box-shadow: 0 0 10px 0 #999; margin-top: 1em; width: 4em;"><br /><br /></div>
給人淡淡的感覺，blur 慢慢設大會給人這種感覺。此時 spred 變得沒有作用(或是用來調深淺，但這用 color 調更合理)。適合拿來營造夢幻的感覺。
3. <div style="border: 1px solid #999; box-shadow: 0 0 10px 0 #999; margin-top: 1em; width: 4em;"><br /><br /></div>
第 2 種加上 border 就變成這種感覺。很多人偏愛這種，但如果 blur 再大一點就會有糊、髒的感覺，調小一點的話不如用第 1 種就好。
4. <div style="border: 1px solid #999; box-shadow: 5px 5px 10px 0 #999; margin-top: 1em; width: 4em;"><br /><br /></div>
加上位移會強調陰影的存在(以上三種都有點像在美化 border)，較少用。

以上，建議 1 > 3 > 2 > 4，若要用 4 的話，也參考一下 3 是怎麼設的 blur 跟 spred 的。

<!--
vi:ft=mkd:nowrap:sw=4:ts=4
-->
