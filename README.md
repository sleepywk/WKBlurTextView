WKBlurTextView
==============

Purpose
--------------
subClass of UITextView can Blur part of texts inside textView.

Show case
--------------
[appetize.io](https://appetize.io/app/e29j6rq3zeu73b4xrhj3cfg3cm?device=iphone5s&scale=75&orientation=portrait&osVersion=9.2)

Supported iOS & SDK Versions
-----------------------------
Support iOS 6+.


3rd Party Library
--------------------
Use [FXBlurView](https://github.com/nicklockwood/FXBlurView) to Implement Blur effect.

WKBlurTextView methods
-----------------------
  
`- (void)blurText:(NSString *)blurText;`

blur text by string.
  
`- (void)blurTexts:(NSArray *)texts;`

blur text by array of strings.
  
`- (void)blurRange:(NSRange)range;`

blur text by NSRange.

`- (void)cleanAllBlur;`

remove all blur effect from textview.

Preview Image
-----------------
![preview image](demo_img_1.png)


Release Notes
-----------------

Version 1.0

- Initial release
