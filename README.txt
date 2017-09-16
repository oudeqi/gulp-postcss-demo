
/*	
	// TODO
	生成CSS雪碧图:postcss-sprites
	这个插件会扫描你CSS中的图像，然后将这些图像合并成一张雪碧图，
	并且按照正确的显示位置重新更新你的代码。
	------------------------------------------------------
	.comment { background: url(images/sprite/ico-comment.png) no-repeat 0 0; }
	.bubble { background: url(images/sprite/ico-bubble.png) no-repeat 0 0; }
	------------------------------------------------------
	.comment { background-image: url(images/sprite.png); background-position: 0 0; }
	.bubble { background-image: url(images/sprite.png); background-position: 0 -50px; }
*/

/*

	// TODO 
	postcss-assets --inserts image dimensions and inlines files.

	// TODO 
	postcss-write-svg --allows you to write simple SVG directly in your CSS.

	// TODO 
	postcss-font-magician --generates all the @font-face rules needed in CSS.
	
	// TODO 
	postcss-px-to-viewport --A plugin for PostCSS that generates viewport units (vw, vh, vmin, vmax) from pixel units.
*/ 


/*
	// TODO 
	postcss-fontpath:
	-----------------------------------
	@font-face {
	  font-family: 'My Font';
	  font-path: '/path/to/font/file';
	  font-weight: normal;
	  font-style: normal;
	}
	-----------------------------------
	@font-face {
	  font-family: 'My Font';
	  src: url("/path/to/font/file.eot") format('embedded-opentype'),
	       url("/path/to/font/file.woff") format('woff2'),
	       url("/path/to/font/file.woff") format('woff'),
	       url("/path/to/font/file.ttf") format('truetype'),
	       url("/path/to/font/file.svg") format('svg');
	  font-weight: normal;
	  font-style: normal;
	}
*/

