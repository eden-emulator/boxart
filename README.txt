Run this :)

find . -type f -iname '*.png' -print0 | xargs -0 -P 16 -I {} optipng {}
