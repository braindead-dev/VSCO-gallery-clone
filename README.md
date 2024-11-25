# VSCO Gallery Clone

This is an ultra-lightweight clone of a VSCO gallery that works seamlessly across all devices. Unlike the official VSCO platform, this gallery does not require a login to view all images, making it more user-friendly for casual viewing. This clone is very barebones, so it's easy to customize and adjust however you'd like.

## Features

- **No login required:** Easily view **all** gallery images without the need for an account.
- **Responsive design:** Optimized for all screen sizes with a responsive grid layout:
  - 4 columns on large desktop screens
  - 3 columns on medium screens
  - 2 columns on mobile devices
- **Simple gallery setup:** Just place your images in the `vsco_images` folder and they will be displayed automatically.

## Setup

1. **Avatar image:**
   - Place your avatar image as `avatar.jpg` inside the `vsco_images` folder. This will be displayed as the profile picture at the top of the page.

2. **Logo image:**
   - Replace the VSCO logo by placing an `icon.png` file inside the `vsco_images` folder. This image will be displayed as the logo in the sidebar (desktop) or header (mobile).

3. **Gallery images:**
   - Add your gallery images to the `vsco_images` folder in the following format: `image1.jpg`, `image2.jpg`, `image3.jpg`, etc. 
   - The gallery will automatically arrange images in a responsive grid layout based on screen size.

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
3. Open the HTML file in any browser to view the gallery.

This simple VSCO gallery clone offers a login-free way to display your images across all devices. Enjoy showcasing your gallery!