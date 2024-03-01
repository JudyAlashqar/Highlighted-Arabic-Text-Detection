# Highlighted Arabic Text Detection
Deep Learning-based Project to detect Highlighted Arabic Text Lines in Pdf Files.

The approach followed is to fine-tune CRAFT detector on augmented dataset, generated initially using "draw_text_image" function from Keras-OCR Toolkit. This funtion did not render Arabic Text Correctly on the images, therefore, the package has been modified to achieve this.
