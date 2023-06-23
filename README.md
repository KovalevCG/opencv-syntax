# opencv-syntax
OpenCV Syntax


// Individual Pixel Access

tmp = img.at<Vec3b>(r, c);
tmp[0] = 128;
tmp[0] = 0;
tmp[2] = 255;

img.at<uchar>(r, c) = 0;
img.at<uint8_t>(r, c) = 0;

// Cycle through pixels 
cv::Mat img = cv::imread("lenna.png");
for(int i=0; i<img.rows; i++)
    for(int j=0; j<img.cols; j++) 
        // You can now access the pixel value with cv::Vec3b
        std::cout << img.at<cv::Vec3b>(i,j)[0] << " " << img.at<cv::Vec3b>(i,j)[1] << " " << img.at<cv::Vec3b>(i,j)[2] << std::endl;






img.at<Vec3b>(r, c)



