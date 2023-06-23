# opencv-syntax
OpenCV Syntax


// Individual Pixel Access
tmp = img.at<Vec3b>(r, c)
tmp[0] = 128;
tmp[0] = 0;
tmp[2] = 255;

img.at<uchar>(r, c) = 0;
img.at<uint8_t>(r, c) = 0;






img.at<Vec3b>(r, c)



