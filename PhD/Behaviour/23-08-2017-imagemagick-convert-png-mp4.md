# Use ImageMagick to convert pngs to mp4 video
- Trim option removes white space
- Delay slows down the fps rate

`convert -trim +repage -delay 60 *.png bg.mp4`