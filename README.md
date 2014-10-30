ColorFromPointImageView
=======================

UIImageView subclass that shows how to retrieve UIColor from a CGPoint in a view.

This little sample project shows the code to retrieve color components from a CGPoint in any view.
For the purpose of a real life example, this uses a UIImageView subclass. 

Usage:

Instantiate your SOXColorFromPointImageView as you would do with any normal UIImageView, and set yourself as delegate.

SOXColorFromPointImageView has an optional protocol method:
`- (void)soxColorFromPointView:(SOXColorFromPointImageView *)view returnedColor:(UIColor *)color atPoint:(CGPoint)point;`

where `view` is the SOXColorFromPointImageView instance;
and `color` is the color retrieved from `point`
SOXColorImageView will call this delegate whenever the user touches on any point of the image.

![alt tag](https://github.com/spagosx/ColorFromPointImageView/blob/master/SOXColorFromPointView/screenshot.png)

Image courtesy of: <a href="https://www.flickr.com/photos/_dchris/" TARGET="_blank">_dchris</a>



