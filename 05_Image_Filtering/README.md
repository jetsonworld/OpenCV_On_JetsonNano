# 이미지 필터링
***
* 다운로드하기
```
git clone https://github.com/jetsonworld/OpenCV_On_JetsonNano.git
```

* [averaging.cpp](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/05_Image_Filtering/averaging.cpp) 컴파일 & 실행하기
```
cd OpenCV_On_JetsonNano/05_Image_Filtering
g++ -ggdb averaging.cpp -o averaging `pkg-config --cflags --libs opencv4`
./averaging
```

![averaging.png](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/05_Image_Filtering/averaging.png)


* [bluring.cpp](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/05_Image_Filtering/bluring.cpp) 컴파일 & 실행하기
```
cd OpenCV_On_JetsonNano/05_Image_Filtering
g++ -ggdb bluring.cpp -o bluring `pkg-config --cflags --libs opencv4`
./averaging
```

![bluring.png](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/05_Image_Filtering/bluring.png)
