# Lane-Detection
Simple Algortithm for lane detection in image and videos. Uses pyhton language and OpenCV library to implement functionality.
Description of algorithm: breaks down video into frames - processes each frame individually. Converts each frame inmage into gray scale - smoothens out the image - uses Hough Transforms for getting egde image. - isolates area of interest (lanes) - averages out the lane lines and demarcates the lane.
