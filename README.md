# PNG to ICNS

<p align="center">
<img width="613" alt="cover_png_to_icns" src="https://user-images.githubusercontent.com/17025808/154702281-8115f8ec-b092-4ba6-9831-e8973b774546.png">
</p>

A Bash / Shell script to convert your PNG images into
Mac OS specific type ICNS (iconset) !

## Image Requirements

- Format should be PNG (transparency isn't mandatory).
- Dimensions need to be **1024x1024** pixels.

## Image Recommendations

- A transparent background will be removed
  (as with the cat icon above)
- Icons with a background generally do no fill the entire 1024x1024 space.
  They are usually inset by about 50px on each side.
  The _rounded-rect-inset.png_ file in this repo provides a template
  that matches the style of many other icons:
  it's a white rounded-rectangle with a transparent border.
  Center your icon within the template, then use the procedure below.

## How to Use

1. Let’s get started by downloading the project,
and move into the newly created folder:

   ```shell
   > git clone https://github.com/BenSouchet/png-to-icns.git
   Cloning into 'png-to-icns'...
   
   > cd png-to-icns
   ```

   Or copy/paste the script file `png_to_icns.sh` in a directory

2. Optionally: Place the **1024x1024** pixels image (`.png`)
you want to convert in the folder
3. Start the script and give the path to the image with
`-i image_path`

   ```shell
   > ./png_to_icns.sh -i <path_to_my_image.png>
   INFO: The icon has been successfully created: ./icon.icns
   ```

4. Done! The new icon has been created, the path of this `.icns`
is indicate on the info message in your terminal.

## Errors / Bugs

If an error occurs, a message with the error(s) info will appear in the terminal.
If you cannot see or understand the error, [open an issue](https://github.com/BenSouchet/png-to-icns/issues).

## Others Resources & Useful links

- [How to create icns files using iconutil](https://stackoverflow.com/questions/12306223/how-to-manually-create-icns-files-using-iconutil)
- [Create icns icons for macos apps](https://www.codingforentrepreneurs.com/blog/create-icns-icons-for-macos-apps)
- [How to use getopts in bash](https://stackoverflow.com/questions/16483119/an-example-of-how-to-use-getopts-in-bash)

## Contibutors

| [<img src="https://github.com/richb-hanover.png" width="60px;"/>](https://github.com/richb-hanover/) |
| :---------------------------------------------: |
| [Rich Brown](https://github.com/richb-hanover/) |

## Author & Maintainer

PNG to ICNS has been created and is currently maintained by [Ben Souchet](https://github.com/BenSouchet).

The code present in this repository is under [MIT license](https://github.com/BenSouchet/png-to-icns/blob/main/LICENSE).
