# 🖼️ Image Watermarking App

A `tkinter` application that lets you add text or logo watermark to your images. It takes an image and let's you decide to add either a text or a logo or image at the right corner of the image. The tkinter app is made using Object-Oriented Programming approach. An example image and logo is provided in this repository for demo.

---

## ⚙️ Workflow of the app

1. Firstly, the app loads when you run `python main.py`
2. There is a `Upload Image` button which you can click to upload an image from your device.
3. The image is displayed on the `Canvas` element.
4. Two buttons appear after the image is displayed, one to `Add text`, and one to `Add logo`.
5.  - After clicking the `Add Text` button, a pop-up appears where you add the text to add as watermark.
    - After clicking the `Add Logo` button, you can select an image/logo to add as a watermark.
6. The text or image/logo will get added as a small watermark on the right corner of the main image.
7. Then, the two add buttons disapear, and a `Save Image` button appears.
8. You can click on the save button to save the image in the original format. (eg., .jpg, .jpeg, .png)

---

## 📚 Libraries used

-   `tkinter`: It is used to create the GUI app, buttons, and canvas.
-   `pillow`: It is used to open, edit, and save the image and logo.

---

## 📽️ Demo

<video controls src="demo.mp4" title="Image Watermark Demo" alt="Image Watermark Demo"></video>
