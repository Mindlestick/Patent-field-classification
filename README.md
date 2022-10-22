# Patent-field-classification
Patent field classification

특허에 대한 설명(text)으로 특허 분류 중 음료제조업(11-)과 가구제조업(32-)을 예측하는 문제이다.
원천 데이터에서 'ipc_main', 'invention_title', 'abstract', 'claims' 컬럼을 합쳐 text라는 결과에 영향을 주는 행을 새롭게 만들었다. 이렇게 생성된 text 컬럼으로 label 데이터를 예측한다.