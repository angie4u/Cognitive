# Custom Vision Services 란?

마이크로소프트에서 최근에 재미있는 서비스를 발표했습니다. 바로 Custom Vision Service 인데요, 사용자들이 아주 손쉽게 이미지를 학습시킬 수 있는 서비스 입니다. 

* [Custom Vision Services](https://www.customvision.ai/)
* [Cognitive Services](https://azure.microsoft.com/ko-kr/services/cognitive-services/)

## Custom Vision Services 접속하기 

[https://www.customvision.ai/](https://www.customvision.ai/) 에 접속한 후 **SIGN IN** 버튼을 눌러 로그인 하시기 바랍니다. 만약 Microsoft 계정이 없으신 경우에는 새로 생성하시기 바랍니다. 
![001](./images/001.JPG)
![002](./images/002.JPG)

회원정보 엑세스 관련 안내문을 확인한 후 **예** 버튼을 눌러 계속 진행하시기 바랍니다. 
![003](./images/003.JPG)

이용약관과 관련된 안내문서를 읽고 체크박스에 **체크표시**를 한 후 **I agree** 버튼을 눌러서 계속 진행하시기 바랍니다.
![004](./images/004.JPG)

## New Project 생성하기

새로운 프로젝트를 생성해 보겠습니다. **New Project** 버튼을 클릭하여 새로운 프로젝트를 생성합니다. 
![005](./images/005.JPG)

새로운 프로젝트의 이름과 설명을 적고, 이미지 분석에 사용될 Domain을 정하는 부분입니다. 아래와 같이 입력하신후 **Create Project** 버튼을 눌러 다음단계로 넘어가시기 바랍니다. 
![006](./images/006.JPG)

아래와 같이 새로운 프로젝트가 생성된 것을 확인하실 수 있습니다. 
![007](./images/007.JPG)

## 이미지 추가하기

학습시킬 이미지가 필요합니다. 이미지 추가를 위해 화면 가운데의 **Add images** 버튼을 누르시기 바랍니다. 
![008](./images/008.JPG)

**Browse local files**를 누른 후, **Training Image/Pyoungyang** 폴더 아래의 이미지들을 전체선택 후 업로드 하시기 바랍니다.  
![009](./images/009.JPG)
![010](./images/010.JPG)

업로드된 이미지들에 **평양냉면**이라는 태그를 추가한 후 **Upload 15 files** 버튼을 눌러 다음단계를 진행하시기 바랍니다. 
![011](./images/011.JPG)
![012](./images/012.JPG)

이미지가 성공적으로 업로드 되었다는 메세지를 확인한 후 **Done** 버튼을 눌러 완료하시기 바랍니다. 
![013](./images/013.JPG)

다음과 같이 이미지가 태그와 함께 성공적으로 업로드 된 것을 확인하실 수 있습니다. 
![014](./images/014.JPG)

**Add images** 버튼을 눌러서 비빔냉면과 잔치국수에 대해서도 위와 동일한 방법으로 이미지를 추가해주시기 바랍니다. 
![015](./images/015.JPG)

이미지를 모두 추가하면 All 탭 아래에 다음과 같이 비빔냉면(15), 잔치국수(15), 평양냉면(15) 가 각각 추가된 것을 확인하실 수 있습니다. 
혹시 추가한 것이 업데이트 되지 않았다면 화면을 새로고침 하시거나, 다른 탭에 갔다가 돌아와 보시기 바랍니다. 
![016](./images/016.JPG)

## 이미지 학습시키기

태그와 함께 추가한 이미지들을 학습시키는 과정이 필요합니다. 아주 간단합니다. 우측 상단의 녹색 **Train** 버튼을 누르시기 바랍니다. 
![017](./images/017.JPG)

이미지를 트래이닝 시키는 페이지가 나온 후, 잠시후에 트레이닝 결과를 확인하실 수 있습니다.
![018](./images/018.JPG)
![019](./images/019.JPG)

이미지가 잘 학습되었는지 간단히 테스트를 해보겠습니다. 상단의 **Quick Test** 버튼을 클릭하시기 바랍니다.
![020](./images/020.JPG)

**Browse local files**를 누른 후 **Test Image** 폴더에 있는 이미지들을 이용하여 테스트를 진행해보시기 바랍니다. 
![021](./images/021.JPG)

## Custom Vision Service 이용하기

**PERFORMANCE** 탭으로 이동하시기 바랍니다.
![022](./images/022.JPG)

**Prediction URL**을 클릭하시기 바랍니다. 
![023](./images/023.JPG)

Prediction API 사용방법을 잘 읽어보시기 바랍니다. **Prediction-Key**및 **URL 주소**는 다음단계에서 사용할 예정입니다. 
![024](./images/024.JPG)