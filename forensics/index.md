
Image Forensics


To find hidden content in images

file cat.jpg
stats cat.jpg
exiftool cat.jpg
lsattr cat.jpg
xxd cat.jpg
strings cat.jpg
binwalk -e cat.jpg

Steganography

steghide
stegseek --crack cat.jpg <wordlist> <output>
