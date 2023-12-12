# ADS5035_01
데이터기반 보안과 프라이버시 Term Project (2023-2)

## Dataset
<https://www.kaggle.com/datasets/birdy654/deep-voice-deepfake-voice-recognition>

Paper : Real-time Detection of AI-Generated Speech for DeepFake Voice Conversion <https://arxiv.org/abs/2308.12734>

## Source
- data_augment.ipynb : generate augment dataset (csv)
- data_augment_sample.ipynb : augment dataset test
- data_eda.ipynb 
- data_split_feature_extracting.ipynb : feature extraction (wav to csv with librosa)
- modeling_csv.ipynb : feature based modeling
- modeling_img.ipynb : image based modeling
- datasets/csv : feature based dataset (+augment)
- datasets/images/spectrogram : image dataset
- result : cw, fgsm results

  
** 하기 폴더는 용량문제로 github에 적재하지 않음, 캐글 원천 데이터셋 참고
- datasets/KAGGLE/AUDIO/FAKE
- datasets/KAGGLE/AUDIO/REAL
- datasets/KAGGLE/AUDIO/data_split/FAKE (data_split_feature_extracting.ipynb 수행 결과 저장)
- datasets/KAGGLE/AUDIO/data_split/REAL (data_split_feature_extracting.ipynb 수행 결과 저장)
