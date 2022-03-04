# PNG to ICNS
<p align="center">
<img width="613" alt="cover_png_to_icns" src="https://user-images.githubusercontent.com/17025808/154702281-8115f8ec-b092-4ba6-9831-e8973b774546.png">
</p>

A Bash / Shell script to convert your PNG images into Mac OS specific type ICNS (iconset) !

## Image Requirements
- Format should be PNG (transparency isn't mandatory).
- Dimensions need to be **1024x1024** pixels.

## How to Use
1. Let’s get started by downloading the project, and move into the newly created folder:
```shell
> git clone https://github.com/BenSouchet/png-to-icns.git
Cloning into 'png-to-icns'...

> cd png-to-icns
```
Or copy/paste the script file `png_to_icns.sh` in a directory

2. Optionally: Place the **1024x1024** pixels image (`.png`) you want to convert in the folder
3. Start the script and give the path to the image as argument:  
`-i` stand for `image_path`
```shell
> ./png_to_icns.sh -i <path_to_my_image.png>
INFO: The icon has been successfully created: ./icon.icns
```
4. Done! The new icon has been created, the path of this `.icns` is indicate on the info message in your terminal.

## Errors / Bugs
If an error occur a message with the error(s) info will appear in the terminal.  
You cannot see or understand the error, [open an issue](https://github.com/BenSouchet/png-to-icns/issues).

## Others Ressouces & Useful links
- [How to create icns files using iconutil](https://stackoverflow.com/questions/12306223/how-to-manually-create-icns-files-using-iconutil)
- [Create icns icons for macos apps](https://www.codingforentrepreneurs.com/blog/create-icns-icons-for-macos-apps)
- [How to use getopts in bash](https://stackoverflow.com/questions/16483119/an-example-of-how-to-use-getopts-in-bash)

## Author & maintainer
PNG to ICNS has been created and is currently maintained by [Ben Souchet](https://github.com/BenSouchet).

The code present in this repository is under [MIT license](https://github.com/BenSouchet/png-to-icns/blob/main/LICENSE).
