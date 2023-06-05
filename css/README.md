## 웹디자인기능사 E-4
### 100%인 경우 좌우 슬라이드
```
.slider {
    flex: 1;
    /* width: calc(100% - 600px); */
    height: 100%;
    background-color: #ddd;
    position: relative;
    overflow: hidden;
}

.slide {
    display: flex;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

.slide a {
    position: absolute;
    top: 0;
    width: 100%;
    height: 100%;
}

.slide a:nth-child(1) {
    left: 0;
}
.slide a:nth-child(2) {
    left: 100%;
}
.slide a:nth-child(3) {
    left: 200%;
}

.slider img {
    width: 100%;
    height: 100%;
    display: block;
    object-fit: cover;
}
```