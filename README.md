# BERT with SentencePiece for Korean text
This is a repository of Korean BERT model with SentencePiece tokenizer.

## SentencePiece tokenizer
한국어 전용 BERT 모델을 만들기 위해서 한국어에 적합한 tokenization 변경할 필요가 있었습니다. 이를 위해 [SentencPiece](https://github.com/google/sentencepiece) tokenization을 사용 하였습니다.

학습 데이터는 위키디피아, 뉴스 데이터 등을 활용하였고 총 1400만 문장정도를 이용해 SetencePiece 모델을 생성하였습니다.
