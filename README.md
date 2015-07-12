# go-image-resize
Command line tool for resizing images written in the Go programming language

## Author
This package was originally implemented by Taylor Hutchison (http://taylorhutchison.com) under the MIT license. 

## Usage
go-image-resize path/to/image percent
	The percent can be written with or without a '%' symbol. I use it in the examples because

## Examples
`./go-image-resize.exe myimage.jpg 50%`
This will output a new jpeg at 50% the original size (maintaining aspect ratio) called 50-myimage.jpg in the same directory.
	
`./go-image-resize.exe myimage.png 225%`
This will output a new png at 225% the original size (maintaining aspect ratio) called 225-myimage.jpg in the same directory.

## Image Formats
go-image-resize currently supports the following image formats:
- jpeg
- png