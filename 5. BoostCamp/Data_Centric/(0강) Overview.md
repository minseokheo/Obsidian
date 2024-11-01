+ Data-Centric : 데이터 중심 AI. Model-Centric AI의 반대 개념
+ OCR(Optical Character Recognition) : 광학 문자 인식
	+ 사람이 직접 쓰거나 이미지 속에 있는 문자를 얻은 다음 이를 컴퓨터가 인식할 수 있도록 하는 기술
	+ 글자 검출(text detection), 글자 인식(text recognition), 정렬기(Serializer)등의 모듈로 구성

+ 진단 평가
	1.  Vision Transformer(ViT)의 특징
		+ Transformer 모델 기반으로 설계
		+ 이미지를 패치 단위로 분할하여 처리
		+ Transformer 모델의 Encoder를 포함
		+ 이미지를 순차적으로 처리하지 않고 병렬적으로 처리
		+ 입력이미지에 위치 정보를 추가하여 위치 인코딩을 사용
	2. Object Detection 모델의 성능을 평가하는 데 사용되는 지표가 아닌 것은?
		+ Mean Average Precision(mAP) : mAP는 객체 탐지 모델의 성능을 평가하는 주요 지표 중 하나
		+ Intersection over Union(IoU) : IoU는 예측된 바운딩 박스와 실제 바운딩 박스 간의 겹침 정도를 측정하는 지표
		+ F1-Score : F1-Score는 정확도와 재현율의 조화 평균으로, 객체 탐지 성능 평가에 사용될 수 있다.
		+ Recall : Recall은 실제 객체 중에서 모델이 올바르게 탐지한 객체의 비율을 나타내는 지표
		+ (정답)Root Mean Squared Error(RMSE) : RMSE는 회귀 분석에서 예측 값과 실제 값 간의 차이를 측정하는 지표
	3. Transformer를 구성하는 Encoder, Decoder에 대한 설명으로 옳지 않은 것은? (틀림)
		+ Encoder는 입력 데이터를 context vector의 형태로 압축
		+ 가장 마지막 Encoder 레이어의 출력 값이 Decoder의 입력 값
		+ Decoder는 입력 데이터를 원래 차원으로 복원
		+ Encoder는 Latent Space라는 저차원 공간에서 입력 데이터를 변환
		+ (정답)Decoder는 입력 데이터의 노이즈를 제거 -> 데이터의 노이즈 제거는 주로 전처리 과정에서 수행
	4. 컴퓨터 비전 분야에서 사용되는 데이터 증강 기법이 아닌 것은?
		+ 이미지 회전
		+ 이미지 스케일링
		+ 채널 셔플
		+ 랜덤 노이즈 추가
		+ (정답)데이터 배치 정규화 -> 신경망의 학습과정에서 각 미니 배치의 평균과 분산을 정규화하여 학습을 안정시키고 가속화하는 기법
	5. OCR을 수행하기 위한 내부 모듈의 순서로 올바른 것은?
		+ Text Detecter - Text Recognizer - Serializer - Parser