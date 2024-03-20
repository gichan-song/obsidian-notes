Threding -> 문턱값 0.5

cv2.threshold(img, threshold_value, value, flag)
- flag: 문턱값 적용 방법 또는 스타일
- cv2.THRESH_BINARY: 픽셀 값이 threshold_value 보다 크면 value, 작으면 0으로 할당
- cv2.THRESH_BINARY_INV: 픽셀 값이 threshold_value 보다 크면 0, 작으면 value로 할당
- cv2.THRESH_TRUNC: 픽셀 값이 threshold_value 보다 크면 threshold_value, 작으면 픽셀 값 그대로 할당
- cv2.THRESH_TOZERO: 픽셀 값이 threshold_value 보다 크면 
- cv2.THRESH_TOZERO_INV



cv2.adaptiveThreshold(img, value, adaptiveMethod, thresholdType, blocksize, C)

- img: Grayscale 이미지
- value: adaptiveMethod에 의해 계산된 문턱값과 thresholdType에 의해 픽셀에 적용될 최대값
- adaptiveMethod: 사용할 Adaptive Thresholding 알고리즘
	- cv2.AP


sudo apt install tesseract-ocr
pip3 install pytesseract

https://github.com/tesseract-ocr/tessdata
kor.traineddata