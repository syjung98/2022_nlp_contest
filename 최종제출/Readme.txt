[최종제출파일 구성]
* 제출코드의 경우 Colab 환경에서 작성되어 런타임 문제로 인해 일부 파일은 epoch 별로 나누어서 코드로그를 구성했습니다.
* 코드로그의 경우 logging으로 생성한 코드로그와 화면캡쳐를 동시에 첨부하였습니다

0. 산업분류 예측값
        • final_predict.csv

1. 기타파일
   1.1) 1. 실습용자료.txt

   1.2) 2. 모델개발용자료.txt

   1.3) left_train.csv
        • 특수기호 ?에 대해 오타로 의심되는 실습용자료의 텍스트 직접 교정한 파일

   1.4) left_test.csv
        • 특수기호 ?에 대해 오타로 의심되는 모델개발용 자료의 텍스트 직접 교정한 파일

2. 제출코드
   2.1) 1. 전처리
        • 전처리 및 데이터 가공.ipynb

   2.2) 2. 모델링 및 최종예측
        • final_predict_kfold0.ipynb : kfold0번째 데이터에 대한 모델링 및 예측
        • final_predict_kfold1.ipynb : kfold1번째 데이터에 대한 모델링 및 예측
        • final_predict_kfold2.ipynb : kfold2번째 데이터에 대한 모델링 및 예측
        • final_predict_kfold3.ipynb : kfold3번째 데이터에 대한 모델링 및 예측
        • final_predict_kfold4.ipynb : kfold4번째 데이터에 대한 모델링 및 예측
        • final_predict.ipynb :  : kfold 데이터에 대한 앙상블 및 최종예측

   2.3) 3. 기타
        • 기타.ipynb : 최종예측까지 실험에 사용된 전처리 및 모델링 코드

3. 코드로그
   3.1) 1. 전처리
        • 전처리 및 데이터 가공.html

   2.2) 2. 모델링 및 최종예측
        • final_predict_kfold0.html : final_predict_kfold0.ipynb 코드 실행 화면 캡쳐
        • final_predict_kfold0.log : final_predict_kfold0.ipynb 코드 실행 로그

        • final_predict_kfold1.html : final_predict_kfold1.ipynb 코드 실행 화면 캡쳐

        • final_predict_kfold2_epoch1~5.html : final_predict_kfold2.ipynb 코드 실행 화면 캡쳐(epoch 1 ~ 5까지의 모델링)
        • final_predict_kfold2_epoch6~7.html : final_predict_kfold2.ipynb 코드 실행 화면 캡쳐(epoch 6 ~ 7까지의 모델링)
        • final_predict_kfold2.log : final_predict_kfold2.ipynb 코드 실행 로그(epoch 6 ~ 7까지의 모델링)

        • final_predict_kfold3_epoch1~5.pdf : final_predict_kfold3.ipynb 코드 실행 화면 캡쳐(epoch 1 ~ 5까지의 모델링)
        • final_predict_kfold3_epoch6~7.html : final_predict_kfold3.ipynb 코드 실행 화면 캡쳐(epoch 6 ~ 7까지의 모델링)
        • final_predict_kfold3_epoch6~7.log : final_predict_kfold3.ipynb 코드 실행 로그(epoch 6 ~ 7까지의 모델링)

        • final_predict_kfold4.html : final_predict_kfold4.ipynb 코드 실행 화면 캡쳐
        • final_predict_kfold4.log : final_predict_kfold4.ipynb 코드 실행 로그

        • final_predict.html : final_predict.ipynb 코드 실행 화면 캡쳐
        • final_predict.log : final_predict.ipynb 코드 실행 로그

