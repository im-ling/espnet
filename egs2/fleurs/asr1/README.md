<!-- Generated by scripts/utils/show_asr_result.sh -->
# Multilingual ASR - SSL + Conformer + Self-condition [XLS-R, Conformer, utt_mvn, 6500 BPE](conf/train_asr_conformer_scctc.yaml)

## Environments
- date: `Sat Oct 22 14:55:21 EDT 2022`
- python version: `3.8.6 (default, Dec 17 2020, 16:57:01)  [GCC 10.2.0]`
- espnet version: `espnet 202207`
- pytorch version: `pytorch 1.8.1+cu102`
- Git hash: `e534106b837ff6cdd29977a52983c022ff1afb0f`
  - Commit date: `Sun Sep 11 22:31:23 2022 -0400`
- Pretrained Model: https://huggingface.co/espnet/wanchichen_fleurs_asr_conformer_scctc

## asr_train_asr_conformer_scctc_raw_all_bpe6500_sp

### Language Identification
|dataset|Accuracy|
|---|---|
|decode_asr_lm_lm_train_lm_all_bpe6500_valid.loss.ave_asr_model_valid.acc.ave_3best/test_all|0.9541 (74237/77809)|

### WER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_asr_lm_lm_train_lm_all_bpe6500_valid.loss.ave_asr_model_valid.acc.ave_3best/test_all|77809|1592160|70.5|26.1|3.4|3.4|32.9|97.0|

### CER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_asr_lm_lm_train_lm_all_bpe6500_valid.loss.ave_asr_model_valid.acc.ave_3best/test_all|77809|10235271|92.2|4.7|3.1|2.6|10.4|97.0|

### TER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_asr_lm_lm_train_lm_all_bpe6500_valid.loss.ave_asr_model_valid.acc.ave_3best/test_all|77809|9622352|91.3|5.6|3.1|2.7|11.4|97.0|

# Multilingual ASR - Self-supervised learning features [HuBERT_large_ll60k, Transformer, utt_mvn, 6500 BPE](conf/train_asr_hubert_large_ll60k_transformer.yaml)

## Environments
- date: `Sun Aug 21 15:18:30 EDT 2022`
- python version: `3.8.6 (default, Dec 17 2020, 16:57:01)  [GCC 10.2.0]`
- espnet version: `espnet 202205`
- pytorch version: `pytorch 1.8.1+cu102`
- Git hash: `45e8cb9173a072f85ee7a7ccbcae06af7c5c484a`
  - Commit date: `Wed Jun 1 14:21:14 2022 +0900`
- Pretrained Model: https://huggingface.co/espnet/wanchichen_fleurs_multilingual_asr_hubert_frontend

### Language Identification
|dataset|Accuracy|
|---|---|
|decode_asr_asr_model_valid.acc.best/dev_all|0.9193 (29070/31622)|
|decode_asr_asr_model_valid.acc.best/test_all|0.9296 (72334/77809)|


### WER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_asr_asr_model_valid.acc.best/test_all|77809|1669969|54.2|38.1|7.8|4.0|49.9|99.7|
|decode_asr_asr_model_valid.acc.best/dev_all|31622|610500|53.4|38.7|7.9|3.5|50.1|99.5|

### CER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_asr_asr_model_valid.acc.best/test_all|77809|10876592|85.1|7.4|7.5|3.2|18.0|99.7|
|decode_asr_asr_model_valid.acc.best/dev_all|31622|3988181|84.7|7.7|7.7|2.8|18.1|99.5|

### TER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_asr_asr_model_valid.acc.best/test_all|77809|9622352|82.8|9.2|8.0|3.4|20.6|99.7|
|decode_asr_asr_model_valid.acc.best/dev_all|31622|3547834|82.4|9.4|8.2|3.0|20.6|99.5|

# English ASR - Self-supervised learning features [Wav2Vec2_large_960hr, Transformer, utt_mvn, 300 BPE](conf/train_asr_wav2vec_960h_transformer.yaml)

## Environments
- date: `Sun Aug 14 14:52:04 EDT 2022`
- python version: `3.8.6 (default, Dec 17 2020, 16:57:01)  [GCC 10.2.0]`
- espnet version: `espnet 202205`
- pytorch version: `pytorch 1.8.1+cu102`
- Git hash: `45e8cb9173a072f85ee7a7ccbcae06af7c5c484a`
  - Commit date: `Wed Jun 1 14:21:14 2022 +0900`
- Pretrained Model: https://huggingface.co/espnet/wanchichen_fleurs_english_asr_wav2vec_frontend

### WER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_asr_asr_model_valid.acc.best/test_all|647|14344|67.1|29.4|3.5|4.6|37.5|99.8|
|decode_asr_asr_model_valid.acc.best/dev_all|388|7935|66.8|29.7|3.6|5.0|38.2| 99.0|

### CER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_asr_asr_model_valid.acc.best/test_all|647|83954|88.6|5.4|6.0|4.8|16.2|99.8|
|decode_asr_asr_model_valid.acc.best/dev_all|388|47051|88.1|6.0|5.9|4.4|16.3|99.0|

### TER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_asr_asr_model_valid.acc.best/test_all|647|39965|7.7|14.9|7.4|4.1|26.4|99.8|
|decode_asr_asr_model_valid.acc.best/dev_all|388|22491|77.3|15.2|7.5|3.8|26.5|99.0|

# English ASR - asr_train_asr_transformer_raw_en_us_bpe150_sp

## Environments
- date: `Thu Jun 16 03:14:31 EDT 2022`
- python version: `3.8.6 (default, Dec 17 2020, 16:57:01)  [GCC 10.2.0]`
- espnet version: `espnet 202205`
- pytorch version: `pytorch 1.8.1+cu102`
- Git hash: `45e8cb9173a072f85ee7a7ccbcae06af7c5c484a`
  - Commit date: `Wed Jun 1 14:21:14 2022 +0900`

### WER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_asr_lm_lm_train_lm_en_us_bpe150_valid.loss.ave_asr_model_valid.acc.ave/dev_en_us|388|7935|5.8|84.3|10.0|7.6|101.8|100.0|
|decode_asr_lm_lm_train_lm_en_us_bpe150_valid.loss.ave_asr_model_valid.acc.ave/test_en_us|647|14344|6.0|83.7|10.2|7.6|101.6|100.0|

### CER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_asr_lm_lm_train_lm_en_us_bpe150_valid.loss.ave_asr_model_valid.acc.ave/dev_en_us|388|47051|41.3|26.5|32.3|6.6|65.3|100.0|
|decode_asr_lm_lm_train_lm_en_us_bpe150_valid.loss.ave_asr_model_valid.acc.ave/test_en_us|647|83954|41.2|26.1|32.7|6.6|65.4|100.0|

### TER

|dataset|Snt|Wrd|Corr|Sub|Del|Ins|Err|S.Err|
|---|---|---|---|---|---|---|---|---|
|decode_asr_lm_lm_train_lm_en_us_bpe150_valid.loss.ave_asr_model_valid.acc.ave/dev_en_us|388|28381|28.0|60.1|11.8|16.4|88.4|100.0|
|decode_asr_lm_lm_train_lm_en_us_bpe150_valid.loss.ave_asr_model_valid.acc.ave/test_en_us|647|50313|27.9|60.6|11.5|16.4|88.6|100.0|
