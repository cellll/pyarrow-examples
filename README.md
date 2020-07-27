PyArrow tutorial
================

설치 
---------------

#### 1) pyarrow python package 설치
    pip install pyarrow
    
#### 2) plasma store 실행

- 옵션
-m : plasma store 의 크기 (bytes)
-s : socket 옵션 (listen)
PLASMA_STORE_PATH

- 실행 예시 
    plasma_store -m 3000000000 -s /tmp/plasma_store
    

