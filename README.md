# Project Shadow

본 문서는 2016.01.31 에 시작한  RPA  연구 프로젝트의 페이지 입니다

본 프로젝트는  Python 3.6 을 기준으로 진행 되었습니다



현 시점까지 작성이 된 프로젝트는 GridOne  사의 AutomateOne 프로그램의 데모 시나리오를 따라한 것이며

Selenium 을 활용한 Xpath 시나리오
일반 마우스-키보드만을 사용한 Drag 시나리요
tesseract 를 활용한 OCR 시나리오
등이 샘플로 완성되었습니다



Xpath 시연 동영상
https://drive.google.com/open?id=1RqEjsplO-KHNr9-ndUMFcbieiIa6foos



Drag 시연 동영상
https://drive.google.com/open?id=19r3G9Ij3_Q6SZIqhj6a63FxZ9tFwjN1s



OCR시연 동영상
https://drive.google.com/open?id=1f7jfr0W1pkaBg17MrOre_9O6WmcOLpW3


================================
## 템플릿 매칭

python 디렉터리 내의 util 디렉터리에 위치한 Scanner 모듈은 템플릿 매칭 코드를 정의 한 모듈이다

Direction 및 MatchTemplate 클래스는 데모에 사용하는 코드이며


original

originalWithScreenShot

함수를 확인하자
이 템플릿 이미지를 사용하여 originalWithScreenShot 함수에서 메인 모니터를 캡쳐하고(마우스 제외)
캡쳐한 이미지에서 템플릿 이미지가 매칭되는 포지션을 잡아 사각형 박스로 감싸 출력한다 (정확도 = 96%)
![source 이미지](https://github.com/kam6512/SimpleRPA/blob/master/samples/TemplateMatchingSample/source.png)
캡쳐화면
</br>
</br>
![source 이미지](https://github.com/kam6512/SimpleRPA/blob/master/samples/TemplateMatchingSample/result.png)
템플릿 매칭 
</br>
</br>
![source 이미지](https://github.com/kam6512/SimpleRPA/blob/master/samples/TemplateMatchingSample/points.png)
결과 화면
