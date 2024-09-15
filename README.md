# VSCO Gallery Clone

This is a basic clone of a VSCO gallery, currently optimized for mobile formatting and not meant for desktop yet. Unlike the official VSCO platform, this gallery does not require a login to view all images, making it more user-friendly for casual viewing.

## Features

- **No login required:** Easily view all gallery images without the need for an account.
- **Mobile-optimized:** The gallery is formatted for mobile and currently doesn't support desktop formatting.
- **Simple gallery setup:** Just place your images in the `vsco_images` folder and they will be displayed automatically.

## Setup

1. **Avatar image:**
   - Place your avatar image as `avatar.jpg` inside the `vsco_images` folder. This will be displayed as the profile picture at the top of the page.

2. **Logo image:**
   - Replace the VSCO logo by placing an `icon.png` file inside the `vsco_images` folder. This image will be displayed as the logo in the top-left corner.

3. **Gallery images:**
   - Add your gallery images to the `vsco_images` folder in the following format: `image1.jpg`, `image2.jpg`, `image3.jpg`, etc. 
   - The gallery will display the images starting with the first column and alternating to the second column for the next image.

### Example folder structure:

```
/vsco_images
    ├── avatar.jpg
    ├── icon.png
    ├── image1.jpg
    ├── image2.jpg
    ├── image3.jpg
    └── ...
```

### Note:
- The gallery dynamically loads images until it encounters a missing image file.
- You can customize the profile name and username by editing the HTML directly.

## How to Use

1. Clone or download the repository.
2. Place your images in the `vsco_images` folder as described above.
3. Open the HTML file in your mobile browser to view the gallery.

This simple VSCO gallery clone offers a login-free way to display your images. Enjoy showcasing your gallery!
