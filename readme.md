
	Sumireneko's QTStyleSheet and ColorScheme Collection  
		for style-sheet-loader and theme-creator-extension( Krita 5 )  

	Version: 1.0 (2023-09-05)  
	Author : L.Sumireneko.M   
	============================================================
	
	This file is customize GUI layout of Krita.(Above Krita version 5.20~)
	This file should be load by style-sheet-loader-extension for Krita
		https://krita-artists.org/t/plugin-style-sheet-loader-extension/62955
		https://invent.kde.org/freyalupen/style-sheet-loader-extension	

	*Reset Style (Use it if you don't want custom Tab and Separator)
		none.qss (It no customize)

	*Light and Dark series (Custom Tab Design)
		krita_style_for_light_v1.0.qss
		krita_style_for_dark_v1.0.qss
		krita_style_for_light_alt_v1.0.qss

	*Flexible series (color variations based by light alt v1.0)
		Tabs and Separators --- by Style sheet loader
		ColorSchemes ---------- by Theme-creator
		It is designed to maintain visibility even when changing colors flexibly.
		
		TwoQSS files x Seven ColorScheme = 14 variation
		You also can use together with krita's default themes
		(BreezeDark/Light,Krita Darker/Dark Orange,Blender etc.)

		emphasised_tab_for_light_v1.0.qss
			flex.light.colors
			flex.lemon.colors
			flex.pale-sky.colors
			flex.pale-rose.colors

		with dark icon set
			Breeze light
			Krita bright

		
		emphasised_tab_for_dark_v1.0.qss
			flex.forest.colors
			flex.dark.colors
			flex.elegant.colors
			flex.abyss-sea.color.colors
		with light icon set
			Breeze high contrast
			Krita blender
			Krita dark
			Krita dark orange
			Krita darker
			Krita neutral
			Krita neutral
			
			
	[How to use this?]
		1.Install style-sheet-loader-extension the plugin for Krita.(into Kita plugin folder)
		2.Put checkmark for the plugin, In Krita preferences(congigure Krita)
			-> Python Plugin Manager, find "Style Sheet Loader" and check it.
		3.Restart Krita
		4.Tools > Script > Load style sheet, and open "Style Sheet Loader" dialog.
		5.Load this file = Qt style sheet (.qss) file by file selector icon in the dialog.
		 You can keep apply a favorite stylesheet from next - 
			time if you checked "Load on start up" in the dialog.

	[Tips] If you want apply any style,it can use none.qss
			(It was text file that discribed comment out only,and do nothing)
	
	[Tips]
		Also This Style sheet can use with color schemes by Theme creator extension together.
		https://krita-artists.org/t/plugin-theme-creator-extension/62953/2
		https://invent.kde.org/freyalupen/theme-creator-extension/
		
		Thanks for Freya Lupen the author who created both of plugins. :D

	[FYI:QT stylesheet reference]
		https://doc.qt.io/qt-6/stylesheet-reference.html#separator-sub 
		https://doc.qt.io/qt-6/stylesheet-examples.html#customizing-qtabwidget-and-qtabbar
