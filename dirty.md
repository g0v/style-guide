# Coding Style
# File Organization
# Naming Convention

# Shadow/陰影

懶人用結論
```css
box-shadow: 0 0 1px 1px #999
```

先回憶一下 [box-shadow](http://www.w3schools.com/cssref/css3_pr_box-shadow.asp) 的設定
>	box-shadow: x y blur spread color inset

我們將陰影大致分為四種(請配合[範例](http://codepen.io/anon/pen/zgrbt)服用)

1.	給人簡潔的感覺，blur 設在 1-3px 都可以給人這種感覺。此時 spread 相當於 border 的作用，而相較於單純使用 border 時 blur 多提供了一點點漸層的感覺。
2.	給人淡淡的感覺，blur 慢慢設大會給人這種感覺。此時 spread 變得沒有作用(或是用來調深淺，但這用 color 調更合理)。適合拿來營造夢幻的感覺。
3.	第 2 種加上 border 就變成這種感覺。很多人偏愛這種，但如果 blur 再大一點就會有糊、髒的感覺，調小一點的話不如用第 1 種就好。
4.	加上位移會強調陰影的存在(以上三種都有點像在美化 border)，較少用。

以上，建議 1 > 3 > 2 > 4，若要用 4 的話，也參考一下 3 是怎麼設的 blur 跟 spread 的。

<!--
vi:ft=mkd:nowrap:sw=4:ts=4
-->
