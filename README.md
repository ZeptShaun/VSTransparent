VSTransparent

設定好的 Visual Studio community 2022 黑色透明主題

# 前置作業

## Visual Studio Installer

* 工作負載 -> 其它工具組 ->

勾選 "Visual Studio 擴充功能開發"

按下 "修改"，進行下載安裝


# Visual Studio Community 2022

開啟 VS2022，不用開啟任何專案，直接按 "不使用程式碼繼續"

* 延伸模組 > 管理延伸模組 >

    搜尋並安裝 "Visual Studio Color Theme Designer 2022" 和 "ClaudiaIDE"

    關閉 Visual Studio 來完成安裝，再重開 Visual Studio


建立 VSTheme Project，設容易辨識的名字

* 工具 > 選項 > ClaudiaIDE

    Expand to IDE 設 True

    File Path 設 圖片位置

* 開啟 "CustomTheme.vstheme"

    Select a base theme 設 Dark

    切換到 All elements

    搜尋下面所有的列表項目，修改顏色屬性為 2A252526

TreeView -> Background
Environment -> Window
Environment -> EnvironmentBackground
Environment -> EnvironmentBackgroundGradientBegin
Environment -> EnvironmentBackgroundGradientEnd
Environment -> EnvironmentBackgroundGradientMiddle1
Environment -> EnvironmentBackgroundGradientMiddle2
Environment -> MainWindowActiveCaption
Environment -> MainWindowInactiveCaption
Environment -> CommandShelfBackgroundGradientBegin
Environment -> CommandShelfBackgroundGradientEnd
Environment -> CommandShelfBackgroundGradientMiddle
Environment -> CommandShelfHighlightGradientBegin
Environment -> CommandShelfHighlightGradientEnd
Environment -> CommandShelfHighlightGradientMiddle
Environment -> CommandBarGradientBegin
Environment -> CommandBarGradientEnd
Environment -> CommandBarGradientMiddle
Environment -> CommandBarToolBarBorder

其它想要透明化的項目，也可以將顏色屬性設為 2A252526

* 最後按下 Apply 即可完成
