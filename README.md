# ๐ BART ๋ชจ๋ธ์ ์ฌ์ฉํ ๋ฌธ์๋ฒ์ญ ๋ฐ ์์ฝ



# ๊ฐ์ 
์ฐ๋ฆฌ๋ ์๋ก์ด ์ ๋ณด๋ฅผ ์ป๊ฑฐ๋, ๊ธฐ์กด์ ์ ๋ณด๋ค์ ์ข ๋ ์ฌํ๋ ๊ณผ์ ์ ๋ํ ์ฐ๊ตฌ๋ฅผ ์์ํ๊ธฐ ์ํด ๋ง์ ๊ฒ์์ ํฉ๋๋ค.

\
์ด ๊ณผ์ ์์ ์ ๋ง์ ๋ผ๋ฌธ๋ค์ ๋ง์ฃผ์น๊ฒ ๋๋๋ฐ, ๋ค์ํ ๋ถ์ผ์ ์ฐ๊ตฌ ๋ฐ ์ ๋ฌธ์ ์ธ ์ ๋ณด ์ต๋์ ์ํ

๊ด์ ์ ์์ด์ ๋ผ๋ฌธ์ ๋ํ ๋ถ์์ ํ์ ์์๋ก ์๋ฆฌ ์ก์์ต๋๋ค.

\
**๋ฅ๋ฌ๋๊ณผ ๋จธ์ ๋ฌ๋ ๋ผ๋ฌธ**์ ์ฝ๋ ๊ณผ์ ์์ ๋งค๋๋ฝ์ง ์๊ฒ ํด์๋๋ ์ด๋ ค์,

๋ ๋ง์ ๋ผ๋ฌธ์ ์ฝ๋๋ฐ ์์ด ์๋น๋๋ ์๊ฐ ๋ฌธ์  ๋ํ ํด๊ฒฐํ  ์ ์๋ ๋ฐฉ์์ ์ฐพ๊ณ ์ ํ์์ต๋๋ค.

\
์ด ๋ชจ๋ธ์ ์๋ฌธ์ผ๋ก ์ฐ์ฌ์๋ ๋ง์ ๋ผ๋ฌธ๋ค์ ํด์ํ๋ ์ ์ ์์ด ๋ฅ์ํ์ง ์์ ์ฌ๋๋ค์๊ฒ 

๋ง์ ์๋ฌธ ๋ผ๋ฌธ์ ์ข ๋ ์ฝ๊ณ  ํธ๋ฆฌํ๊ฒ ๋ณผ ์ ์๋๋ก ํ์ผ๋ฉฐ

\
์ฃผ ํ๊ฒ์ **IT ๊ด๋ จ ๋ผ๋ฌธ ๋ฒ์ญ ๋ฐ ์์ฝ**์ผ๋ก ์ ํ์ต๋๋ค.

\
๋ฌธ์๋ฒ์ญ๊ณผ ์์ฝ์ ํฉํ ํ์ดํ๋ผ์ธ์ ๊ตฌ์ถํ์ฌ ์์ด์๋ฌธ์ ๋ฃ์ผ๋ฉด output์ผ๋ก ๋ฒ์ญ๋ ํ๊ธ์๋ฌธ๊ณผ

๋์จ ํ๊ธ์๋ฌธ์ด ๋ค์ input์ผ๋ก ๋ค์ด๊ฐ output์ผ๋ก ํ๊ธ์์ฝ๋ฌธ์ด ๋์ค๊ฒ ์ค๊ณํ์์ต๋๋ค.

# ์์ฑ๋ ๋ชจ๋ธ


<br><br>
# Dataset
- ๋ฌธ์๋ฒ์ญ AI Hub ํ๊ตญ์ด-์์ด ๋ฒ์ญ ๋ง๋ญ์น(๊ธฐ์ ๊ณผํ) : https://aihub.or.kr/aidata/30719 
- ๋ฌธ์์์ฝ AI Hub ๋ผ๋ฌธ์๋ฃ ์์ฝ(ํ๊ธ) : https://aihub.or.kr/aidata/30712 

์ด ๋ฐ์ดํฐ ๊ฐ์

| Data                | # total size   |
| ------------        | -------------: |
| EN to KR (ICT part) |        350,000 |
| Text to Summary     |        180,000 |

# BART

BART๋ Bidirectional Auto-Regressive Transformer์ ์ฝ์์ด๋ฉฐ
BERT์ GPT๋ฅผ ํ๋๋ก ํฉ์น ํํ๋ก, ๊ธฐ์กด seq2seq transformer ๋ชจ๋ธ์\
์๋ก์ด Pre-training objective๋ฅผ ํตํด ํ์ตํ์ฌ ํ๋๋ก ํฉ์น ๋ชจ๋ธ์๋๋ค.

BART ๋ชจ๋ธ์ด ๋์ค๋ฉฐ ์ฌ๋ฌ ์์ฐ์ด ๋ฒค์น๋งํฌ์์ sota๋ฅผ ๋ฌ์ฑํ ์ญ์ฌ๋ฅผ ๋ณด๊ณ \
๊ณตํต๋ ๋ชจ๋ธ๋ก BART๋ฅผ ์ ์ ํ๊ฒ ๋์์ต๋๋ค.

# Model Used

| Model               | # Purpose        |
| ------------        | -------------: |
| mBART 50 (large)    |    translation |
| KoBART              |  Summarization |


## mBART 50_large (Translate thesis EN to KR)

mBART๋ 50๊ฐ์ ์ธ์ด๋ก ๊ตฌ์ฑ๋ ๋ง๋ญ์น๋ฅผ ํ์ฉํ๋ ๋ชจ๋ธ์ผ๋ก์จ\
๊ทธ ์ค tokenizer์ ์์ด(en-XX)์ ํ๊ตญ์ด(ko-KR)๋ฅผ ์ ์ฉํ์ฌ ์ฌ์ฉํ์ต๋๋ค.\
mBART๋ BART์ ์ ์ฌํ๊ฒ ์ฌ์ ํ์ต ๋จ๊ณ์์ ์๋ณธ ๋ฌธ์ฅ์ ๊ณ ์๋ก ํผ์ํ์ฌ\
์๋ ฅ ๋ฐ์ดํฐ๋ฅผ ๋ง๋  ํ ์ด๋ฅผ ์๋ณธ ๋ฌธ์ฅ์ผ๋ก ๋ณต์ํ๋ ์์์ ํ์ตํฉ๋๋ค.\
\
์ด๋, ์๋ณธ ๋ฌธ์ฅ์ ํผ์ํ๋ ๋ฐฉ๋ฒ(Noising Scheme)์ผ๋ก๋ ์ฐ์๋ ๋จ์ด๋ฅผ ํ๋์
[MASK]ํ ํฐ์ผ๋ก ์นํํ๋ Text Infilling ๋ฐฉ๋ฒ๊ณผ\
์๋ ฅ ๋ด์์ ๋ฌธ์ฅ์ ์์๋ฅผ ๋ฐ๊พธ๋ Sentence Permutation๋ฐฉ๋ฒ ๋ ๊ฐ์ง๋ฅผ ํ์ฉํฉ๋๋ค.

## KoBART (Summarize KR thesis)

KoBART๋ SKT๊ฐ ๊ฐ๋ฐํ ๋ชจ๋ธ๋ก์ ๊ธฐ์กด BART ๋ชจ๋ธ์์ ์ฌ์ฉ๋ Text Infilling ๋ธ์ด์ฆ ํจ์๋ฅผ ์ฌ์ฉํด\
์ฝ 40GB ์ด์์ ํ๊ตญ์ด ํ์คํธ์ ๋ํด ํ์ตํ ํ๊ตญ์ด encoder-decoder ์ธ์ด ๋ชจ๋ธ์๋๋ค.

# DATA PRE-PROCESSING
- AI Hub์ ๋ฐ์ดํฐ๋ ์ฒ ์ ํ ํ์ง ๊ด๋ฆฌ๊ฐ ์ด๋ฃจ์ด์ง ๋ฐ์ดํฐ๋ก์จ ํน๋ณํ ์ ์ฒ๋ฆฌ ๊ณผ์ ์ด ํ์์น ์๋ค๊ณ  ํ๋จํ์ต๋๋ค.

## Translation

- ํ๊ตญ์ด-์์ด ๋ฒ์ญ ๋ง๋ญ์น ์ค ๊ธฐ์ ๊ณผํ ๋ถ์ผ 35๋ง๊ฐ๋ฅผ ๋ค์ด๋ก๋ ํ์ผ๋
ํ์ต ๊ณผ์ ์์์ ์์์๊ฐ์ ์ค์ด๊ธฐ ์ํด ๊ทธ ์ค ๋น๋ฐ์ดํฐ์ ์ปดํจํฐ ์นดํ๊ณ ๋ฆฌ์ ๋ฐ์ดํฐ\
์ด 15๋ง5์ฒ๊ฐ ๋ฐ์ดํฐ๋ฅผ ์ฌ์ฉํ์ต๋๋ค.

## Summarization

- ๋ผ๋ฌธ์๋ฃ ์์ฝ(ํ๊ธ) ์ค ํ์ ๋ผ๋ฌธ(์ ์ฒด์์ฝ) 18๋ง๊ฐ์ ๋ฐ์ดํฐ๋ฅผ jsonํ์ผ๋ก์จ ๋ค์ด๋ก๋ ๋ฐ์๊ณ \
๋ฐ์ดํฐ ์ค 'text'์ 'summary' ์ฆ '์๋ฌธ'๊ณผ '์์ฝ๋ฌธ'๋ง ๊ฐ์ ธ์ ์ฌ์ฉํ์ต๋๋ค. 

- ๊ธฐ์กด BART๋ชจ๋ธ์ ๋ธ์ด์ฆ๋ฅผ ๋ง๋ค์ด๋ด๋ Noising Scheme ๋ฐฉ๋ฒ์ด ์์ง๋ง
AI Hub์ ๋ฐ์ดํฐ๋ ๋งค์ฐ ๊น๋ํ ์ ๋๋ ๋ฐ์ดํฐ์ฌ์\
๋ธ์ด์ฆ ์ถ๊ฐ๊ฐ ํ์ํ๋ค ํ๋จ, Selenium์ ํตํด ์๋์ผ๋ก 1๋ง๊ฐ์ ์์ด๋ฌธ์ฅ์ ๋ฃ๊ณ \
์ผ์ฑ SR Translation(https://translate.samsung.com/) ๋ฒ์ญ๊ธฐ์ ๋๋ฆฐ ๋ฒ์ญ๋ฌธ(ํ๊ธ)์ ํฌ๋กค๋งํด์ ๋ธ์ด์ฆ ๋ฐ์ดํฐ๋ฅผ ํ๋ํ์์ต๋๋ค.\
ํ๋ํ ๋ธ์ด์ฆ ๋ฐ์ดํฐ๋ฅผ ๊ธฐ์กด ๋ฐ์ดํฐ 14๋ง๊ฐ + ๋ธ์ด์ฆ ๋ฐ์ดํฐ 1๋ง๊ฐ(๋ฒ์ญ ํ ๋์จ ํ๊ธ) ์ด 15๋ง๊ฐ๋ฅผ KoBART ๋ชจ๋ธ๋ก ํ์ต์ ์งํํ์ต๋๋ค.


# Modeling

- Huggingface API (tokenizer, model)์ download ๋ฐ import
```python
!pip install git+https://github.com/huggingface/datasets.git@master
from transformers import MBartForConditionalGeneration, MBart50TokenizerFast
model = MBartForConditionalGeneration.from_pretrained("facebook/mbart-large-50")
tokenizer = MBartTokenizer.from_pretrained("facebook/mbart-large-50", src_lang="en_XX", tgt_lang="ko_KR")
```
- ์ ์ฒ๋ฆฌ๊ฐ ๋๋ ๋ฐ์ดํฐ zip์ ์ด์ฉํด ํ๋์ data ์์ฑ

```python
data = []
with open("/content/en.csv") as f1, open("/content/ko.csv") as f2:
    for src, tgt in zip(f1, f2):
      data.append(
          {
                  "ko": tgt.strip(),
                  "en": src.strip()
          }
      )
print(f'total size of data is {len(data)}')
```

- ๋์๋๋ฆฌ ํํ๋ก ์ ํ ํ ํ ํฐํ ๋ฐ ์ ์ํ ๊ณผ์ ์ ์งํ

```python
def preprocess_function(examples):
    inputs = [doc for doc in examples["en"]] 
    model_inputs = tokenizer(inputs, max_length=1024, truncation=True) 
    with tokenizer.as_target_tokenizer():
        labels = tokenizer(examples["ko"], max_length=1024, truncation=True)
    model_inputs["labels"] = labels["input_ids"]
    return model_inputs
```

```python
tokenized_data = data.map(preprocess_function, batched=True)
```

- ๋ฐ์ดํฐ์์ pre-trained๋ ๋ชจ๋ธ๋ก ํ์ตํฉ๋๋ค.

----์ ๋ฐฉ์๊ณผ ๋น์ทํ ๋ฐฉ์์ผ๋ก ๋ฌธ์์์ฝ๋ ์งํ๋ฉ๋๋ค (ํด๋น ipynbํ์ผ ์ฐธ์กฐ)----


# Result

## Translation 

Colab pro+ ๊ธฐ์ค ํ ๋น๋ GPU๋ณด๋ค ํ์ต์ ๋ง์ GPU๋ฅผ ์ฌ์ฉํ๊ฒ ๋๋ฉด์ ๋ค์ด๋๋ ํ์์ด ์ผ์ด๋\
Batch_size๋ฅผ 8, epoch์ 15๋ก ์ค์ ํ๊ณ  ํ์ต์์ผฐ์ต๋๋ค.

| Epoch               | Training Loss    | Validation Loss|
| -------------:      | -------------:   | -------------: |
|1	                  |  0.843600        |0.789460        |
|2	                  |  0.684200	     |0.722583        |
|3	                  |  0.546200	     |0.717286        |
|4	                  |  0.431400	     |0.740622        | 
|5	                  |  0.335800	     |0.791957        |
|6	                  |  0.272400	     |0.853283        |
|7	                  |  0.197200	     |0.931563        |
|8	                  |  0.143800	     |0.993216        |
|9	                  |  0.111800	     |1.042014        |
|10                   |  0.083300	     |1.086850        |

๊ทธ๋ฌ๋ 5 epochs๋ถํฐ Training Loss๋ ๊พธ์คํ ์ค์ด๋ค์ง๋ง Validation Loss๊ฐ ๋์ด๋๋
Overfit ํ์์ด ์ผ์ด๋์ 10 epochs์์ ํ์ต์ ์ค๋จํ๊ณ  5 epochs์ ์ฒดํฌํฌ์ธํธ๋ก ์ ์ฅ๋์ด์๋\
๋ชจ๋ธ๊ณผ tokenizer๋ก ๋ฒ์ญ๊ธฐ๋ฅผ ๋๋ ค๋ณด์์ต๋๋ค.


์์ด ์๋ฌธ
`'Build a Machine Learning web application from scratch in Python with Streamlit. We use real world data to build a machine learning model. In the first part you learn how we analyze the data and build our model, and in the second part we build the web app using streamlit.'`

ํ๊ธ ๋ฒ์ญ๋ฌธ
`'Streamlit์ผ๋ก Python์์๋ถํฐ ๋จธ์ ๋ฌ๋ ์น ์ ํ๋ฆฌ์ผ์ด์์ ๊ตฌ์ฒดํ ์์ผ ๋๋๋ค. ์ค์ธ๊ณ ๋ฐ์ดํฐ๋ฅผ ์ด์ฉํด ๋จธ์ ๋ฌ๋ ๋ชจ๋ธ์ ๊ตฌ์ถํ๋ค. ์ฒซ ๋ฒ์งธ ํํธ์์๋ ๋ฐ์ดํฐ ๋ถ์ ๋ฐฉ๋ฒ์ ๋ฐฐ์ฐ๊ณ  ๋จธ์ ๋ฌ๋ ๋ชจ๋ธ์ ๊ตฌ์ถํ๋ ๋ ๋ฒ์งธ ํํธ์์๋  streamlit์ ์ด์ฉํด ๋จธ์ ๋ฌ๋์ ์ด์ฉํ ์น ์ฑ์ ๊ตฌ์ถํ๋ค.'`

- ๋ฎ์ง ์์ Validation Loss์๋ ๋ถ๊ตฌํ๊ณ  ์ข์ ์ฑ๋ฅ์ ๋ณด์๋๋ค.
- ๋ํ IT ์นดํ๊ณ ๋ฆฌ์ ๋ฐ์ดํฐ๋ฅผ ํ์ต์ํจ ๊ฒฐ๊ณผ '๋จธ์ ๋ฌ๋'๋ฑ ๊ด๋ จ ์ ๋ฌธ์ฉ์ด์ ๋ํ ํด์๋ ํ๋ฅญํ ํด๋ด๋ ๋ชจ์ต์ ๋ณด์๋๋ค.

## Summarization

๋ฒ์ญ์์ GPU ๋ฉ๋ชจ๋ฆฌ ์ด์๋ฅผ ๊ฒช์๊ณ  ๋ฐ์ดํฐ์ ์ ๋ํ ๋ ๋ง์์ ๋ฒ์ญ๊ณผ ๋์ผํ๊ฒ
Batch_size๋ฅผ 8, epoch์ 15๋ก ์ค์ ํ๊ณ  ํ์ต์์ผฐ์ต๋๋ค.

| Epoch               | Training Loss  | Validation Loss|
| -------------:      | -------------: | -------------: |
|1	                  |  2.122000      | 	2.020537      |
|2	                  |  1.966700	     |  1.986229      |
|3	                  |  1.912900	     |  1.972917      |
|4	                  |  1.765300      | 	1.974346      | 
|5	                  |  1.757700      | 	1.978424      |
|6	                  |  1.621700      | 	1.988834      |
|7	                  |  1.667400      | 	1.998288      |
|8	                  |  1.625300	     |  2.010657      |
|9	                  |  1.558700	     |  2.018661      |
|10                   |  1.575400	     |  2.025263      |


๊ทธ๋ฌ๋ ํ์ต์ด ์์๋์์ง๋ง ์ฒ์๋ถํฐ Training, Validation Loss์ ๊ฐ์ด 2์ด์์ผ๋ก ๋์๊ณ 
ํ์ต์ด ์งํ๋ ์๋ก loss๊ฐ ๋ฎ์์ก์ผ๋ 5epoch ์ดํ๋ถํฐ Validation Loss๊ฐ์ด ์ฌ๋ผ๊ฐ๋
Overfit ํ์์ด ๋ํ๋ฌ์ต๋๋ค.

๊ฒฐ๊ตญ ์์ ๋ง์ฐฌ๊ฐ์ง๋ก 10 epochs์์ ํ์ต์ ์ค๋จํ๊ณ  5 epochs์ ์ฒดํฌํฌ์ธํธ๋ก ์ ์ฅ๋์ด์๋\
๋ชจ๋ธ๊ณผ tokenizer๋ก ์์ฝ๋ชจ๋ธ์ ๋๋ ค๋ณด์์ต๋๋ค.

- ์์ด์์ ๋ฒ์ญ๋ ํ๊ธ ์๋ฌธ
`'์ธ์ด๋ก ๋ ํ์คํธ๋ฅผ ๋คํธ์ํฌ ๋ถ์ ๋์์ผ๋ก ํ์ฌ, ๊ทธ ๋ด์ฉ์ ๋ถ์ํ๋ ๋ฐฉ๋ฒ์ ์ธ์ด ๋คํธ์ํฌ  ๋ถ์(language network  analysis)์ด๋ผ๊ณ  ํ๋ค. 
์ธ์ด ํ์คํธ๋ก ํํ๋ ๋ฉ์์ง์ ๋ด์ฌ๋ ๋ค์ํ ํน์ฑ๋ค์ ๋ํ๋ด๋ ๊ฐ๋๋ค์ ์ถ์ถํ๊ณ , ๊ทธ๋ค ๊ฐ์ ํ์ฑ๋๋ ์๋ฏธ์ ๊ด๊ณ์ ์์ฑ๋ค์ ํ์ํ๊ณ ์ ํ  ๋ ์ธ์ด ๋คํธ์ํฌ ๋ถ์ ๋ฐฉ๋ฒ์ ์ฌ์ฉํ๋ฉด ๋งค์ฐ ์ ์ฉํ๋ค. 
์ผ๋ฐ์์ผ๋ก ์ธ์ด ํ์คํธ์ ํน์ฑ์ ๋ํ๋ด๋ ๊ฐ๋์ ํค์๋(๋๋ ๋จ์ด)๋ก ํํ๋๋ฉฐ, ๋ช์ฌํํ์ ๋จ์ด, ํน์ ํ ๋ฒ์ฃผ์ ์ํ๋ ๋จ์ด, ๊ฐ์ฑ์ ๋ํ๋ด๋ ๋จ์ด ๋ฑ์ผ๋ก ๋ํ๋๋ค.
๋ฐฉ๋ฒ๋ก ์ผ๋ก ๋ณด๋ฉด, ์ธ์ด ๋คํธ์ํฌ ๋ถ์์ ๋ด์ฉ๋ถ์(content analysis) ๋ฐฉ๋ฒ์ ๋ฒ์ฃผ์ ํด๋น๋๋ค๊ณ  ๋ณผ ์ ์๋ค. 
์ํต์์ธ ๋ด์ฉ๋ถ์์ ์ฐ๊ตฌ๋ผ๋ฌธ, ์ธ๋ก ๊ธฐ์ฌ, ์ธํฐ๋ทฐ์๋ฃ, ๊ธฐ๋ก์๋ฃ ๋ฑ๊ณผ ๊ฐ์ ์ธ์ด ํ์คํธ์์ ํน์ ํ ๊ฐ๋๋ค(์์, ๋๋, ์ฃผ์  ๋ฑ์ ํน์ฑ)์ด ๋ฑ์ฅํ๋ ๊ฒฝํฅ์ ๋น๋์ ๊ฐ์ ํต๊ณ์  ๋ฐ์ดํฐ๋ก  ํ์ํ๋  ๋ฐฉ๋ฒ์ด๋ค. 
๋ฐ๋ฉด์, ์ธ์ด ๋คํธ์ํฌ ๋ถ์์ ์ธ์ด ํ์คํธ๋ก๋ถํฐ ํน์ ํ ๊ฐ๋๋ค์ ๊ด๊ณ๋ฅผ ํ์ํ๊ณ , ์ด๊ฒ์ ๋คํธ์ํฌ๋ก ๊ตฌ์ฑํ์ฌ, ๊ณ๋์์ธ ํน์ฑ์ ๋ถ์ํ๋ ๊ฒ๊น์ง ํ๋๋ ๋ด์ฉ๋ถ์ ๋ฐฉ๋ฒ์ด๋ค. 
์ด๋ฌํ ๊ฐ๋๋ค ๊ฐ์ ๊ด๊ณ๋ฅผ ์ธ์ด ๋คํธ์ํฌ(language network)๋ก ํํํ๋ค'`

- ํ๊ธ ์์ฝ๋ฌธ
`" ์ธ์ด ํ์คํธ๋ก ํํ๋ ๋ฉ์์ง์ ๋ด์ฌ๋ ๋ค์ํ ํน์ฑ๋ค์ ๋ํ๋ด๋ ๊ฐ๋๋ค์ ์ถ์ถํ๊ณ , ๊ทธ๋ค ๊ฐ์ ํ์ฑ๋๋ ์๋ฏธ์ ๊ด๊ณ์ ์์ฑ๋ค์ ํ์ํ๊ณ ์ ํ  ๋ ์ธ์ด ๋คํธ์ํฌ ๋ถ์ ๋ฐฉ๋ฒ์ ์ฌ์ฉํ๋ฉด ์์ฃผ ์ ์ฉํ๋ค.  ์ผ๋ฐ์์ผ๋ก ์ธ์ด ํ์คํธ์ ํน์ฑ์ ๋ํ๋ด๋ ๊ฐ๋์ ํค์๋๋ก ํํ๋๋ฉฐ, ๋ช์ฌํํ์ ๋จ์ด, ํน์ ํ ๋ฒ์ฃผ์ ์ํ๋ ๋จ์ด, ๊ฐ์ฑ์ ๋ํ๋ด๋ ๋จ์ด ๋ฑ์ผ๋ก ๋ํ๋๋ค." `

- ์ฒ์ ๋ณด์์ ๋๋ ๋ฌธ์ฅ์ด ์์ฐ์ค๋ฝ๊ณ  ํ๊ธฐ์ ์ผ๋ก ๋จ์ด์ ๋ฌธ์ฅ์ ์๊ฐ ์ค์ด๋ค์ด ์์ฝ์ ์ฑ๊ณตํ ๊ฒ์ผ๋ก ๊ฐ์ฃผํ์ผ๋
์๋ฌธ์ ๋ด์ฉ์ ์์ฝํ ๊ฒ์ด ์๋ ์ฝ 150์์ ์ด ๋์ด๊ฐ๋ฉด ๋ฌธ์ฅ์ ์๋ฅด๊ณ  ๋๋ด๋ฒ๋ ค ๊ทธ ์ดํ์ ๊ธ์ ์๋ตํด๋ฒ๋ฆฌ๋ ๊ฒฐ๊ณผ๊ฐ ๋์์ต๋๋ค.

# Pipeline

- ์ถํ ์ถ๊ฐ ์์ 

# Web translator application

- pyscript๋ฅผ ์ด์ฉํ ์น ๋ฒ์ญ๊ธฐ ์ฌ์ดํธ ์ฐ๊ตฌ

- ์ถํ ์ถ๊ฐ ์์ 


# ๋ง์น๋ฉฐ...

์ผ์ฃผ์ผ๋์ ์งํ๋์๋ ํ๋ก์ ํธ (05/25 ~ 06/02)

์ฒซ์งธ๋ ์ ์ฃผ์  ์ ์ ์์ ๋ฐ๋ก ๋ผ๋ฌธ ๋ฒ์ญ ๋ฐ ์์ฝ ์์ด๋์ด๊ฐ ๋์๊ณ 

๊ทธ ์ดํ ๋ฐ์ดํฐ ์ ์ ๋ถํฐ ํ์ดํ๋ผ์ธ ๊ตฌ์ถ ๋ฐ ์น ๊ฐ๋ฐ๊น์ง

์ฃผ๋ง,๊ณตํด์ผ๊น์ง ๋ฐ๋ฉํ๋ฉฐ ์ด์ฌํ ํด์ฃผ์  ์กฐ์๋ถ๋ค

์ ๋ง ์๊ณ  ๋ง์ผ์จ์ต๋๋ค ใฝ๏ผโงโกโฆ๏ผใ




## ์ฐธ๊ณ  ์๋ฃ

- https://www.ajunews.com/view/20201210114639936
- https://dladustn95.github.io/nlp/BART_paper_review/
- https://github.com/SKT-AI/KoBART#how-to-install
- https://chloelab.tistory.com/34
- https://deepkerry.tistory.com/32
- https://dladustn95.github.io/nlp/BART_paper_review/
- https://dacon.io/competitions/official/235829/codeshare/4047
- https://www.koreascience.or.kr/article/CFKO202130060780846.pdf
- https://www.koreascience.or.kr/article/JAKO202116954611776.pdf
- https://jiwunghyun.medium.com/acl-2020-bart-denoising-sequence-to-sequence-pre-training-for-natural-language-generation-7a0ae37109dc
