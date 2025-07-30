1. OCR (Optical Character Recognition) – The “reader” that understands images
OCR is the technology that can look at an image and recognize the letters and words in it. Think of it like a robot that reads your photo like a human would. We'll use Tesseract, one of the best open-source OCR engines, and connect it with Python using a library called pytesseract. This helps us extract all the text from our note images in just a few seconds.

2. Image Preprocessing – Cleaning the image before reading
OCR is smart, but it works much better when the images are clean and clear. That’s where image preprocessing comes in. With tools like OpenCV, we’ll improve the quality of the image: convert to black and white, remove noise, sharpen text — so OCR can “see” the writing better. It’s like cleaning a window before trying to read through it.

3. Batch Automation – Processing many images at once
Instead of handling one image at a time, we’ll write scripts that automatically process an entire folder of images. That means we can scan a book or handwritten notes, drop all the images into one folder, and the system will handle them all in one go — saving us hours of manual work.

4. Editable Output – Letting us manually touch up the result
The extracted text won’t always be perfect, so we’ll make sure the output can be reviewed and edited. At first, we’ll just save the result as .txt files or open them in Notepad/Google Docs. Later, we can build or connect a simple web editor to make the process smoother — but that's optional for now.
