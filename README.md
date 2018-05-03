# Usage

```` sh
docker run --rm -ti \
    --workdir '/code' \
    -v "${PWD}:/code" \
    mathieubrun/magick:latest -resize 180x180^ "image.jpg" "image_thumb.jpg"
````