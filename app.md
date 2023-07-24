#1 Edit image on nautilus
  sudo apt install nautilus-image-converter
  nautilus -q
https://fostips.com/right-click-resize-rotate-photo-ubuntu/

#2 Transparent top panel Ubuntu
  sudo apt install gnome-shell-extension-manager
  https://fostips.com/get-transparent-top-panel-ubuntu-20-10/#:~:text=Enable%20Top%20Bar%20Transparency%20via%20Gnome%20Extension%3A&text=First%20open%20terminal%20by%20either,T%20shortcut%20key%20on%20keyboard.&text=4.,and%20hit%20Enter%20to%20search.
  
#3 Convert WebP Images to PNG and JPEG
  sudo apt install webp
  dwebp image.webp -o final.png
  ls -l final.png
  dwebp image.webp -o final.jpeg
  ls -l final.jpeg 
