# cs450
Computer Vision Projects - (Hough Transform &amp; Edge Detection, Image Segmentation, Image Stitching, QR Code Reader)

Hough Transform/Edge Detection : Mathematical underpinnings and implementation of Canny Edge Detection, along with application using the Hough transform to detect circles in images.

Image Segmentation : Allows for human seeding of labels, and performs segmentation by implementation of the graph cut algorithm. Pixels are assigned weights tied to them being labelled as foreground or background, as well as weights comparing neighboring pixels (using Kernel Density Estimation), and we build a graph structure which we use to minimize the cost of a cut between background and foreground classification.

Image Stitching : Program that performs panoramic stitching of various photos that are taken in succession. Uses SIFT features and RANSAC to find points that estimate the homography transformation to stitch images together.

QR Code Reader : Program that interprets images of QR codes and returns the URL. Reads QR codes of various rotations, with noise, and also a simple implementation of a barcode reader.
