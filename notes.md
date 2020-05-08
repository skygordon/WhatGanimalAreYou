
# asset list

* images: goldenfloofa, waterdog, waterflower, owlish, floofle, flamin
* sounds: bubbles

# cheat sheet

wav to m4a conversion:

for i in *; do ffmpeg -i "$i" -c:a libfdk_aac -b:a 128k -ac 1 "${i%.*}.m4a"; done
