# QR-Code-Scanner-Using-OpenCVThis code captures video from the webcam and detects barcodes or QR codes in real-time. Here's a breakdown:

Imports: It uses cv2 (OpenCV) for image processing, numpy for array manipulation, and pyzbar to decode barcodes/QR codes.
decoder function:
Converts each frame to grayscale for better barcode detection.
Detects barcodes/QR codes and draws a green polygon around them.
Displays the decoded data and type on the video frame and prints it in the console.
Main loop:
Captures video from the webcam.
Processes each frame using the decoder function.
Displays the frame and exits when 'q' is pressed.

