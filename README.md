# webgl_tetris_lab01
Assignment 1a for VU Foundations of Computer Graphics

All images from pexels.com under CC0 License.

This program requires a webserver to run, because of the image restrictions. (Tested with xampp - Apache webserver)

The texture image is quite big (~ 9mb). I hope this doesn't count as inefficient and slow. 
The picture could be made smaller, but as I run it locally the download-time is negligible.


The tetromino doesn't rotate around its center, but around a vertex of a unit.
This is because elsewise the imaginary unit raser of the two tetrominos wouldn't fit together.
If i increase the unitlength, the tetrominos don't fit together anymore.
Despite they move one unit size, they don't fit together, because the startpoint of the two tetrominos doesn't change.


