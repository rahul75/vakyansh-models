# Vakyansh Open Source Models

## Pretrained Models

| Pretrained Model | Architecture | Pretrained Hours          | 
|------------------|----------|---------|
| [hindi_pretrained_4kh](https://storage.googleapis.com/vakyaansh-open-models/hindi/pretrained/hindi_pretrained_4kh.pt) | Base |  4200             | 
| [kannada_pretrained_1400h](https://storage.googleapis.com/vakyaansh-open-models/kannada/pretrained/kannada_pretrained_1400h.pt) | XLSR | 1400               |


## Finetuned Models
| Language | Pretrained Model | Architecture | Finetuned Model | Finetuned Hours | Dictionary |
|----|--------|----|-----|-------------------|-------|
| Hindi | hindi_pretrained_4kh | Base | [hindi_pretrained_4kh](https://storage.googleapis.com/vakyaansh-open-models/hindi/finetuned/hindi_finetuned_4kh.pt) |   4200             | [dict](https://storage.googleapis.com/vakyaansh-open-models/hindi/dictionary/dict.ltr.txt) |
| Kannada | kannada_pretrained_1400h | XLSR | [kannada_finetuned_570h](https://storage.googleapis.com/vakyaansh-open-models/kannada/finetuned/kannada_finetuned_570h.pt) |  570             | [dict](https://storage.googleapis.com/vakyaansh-open-models/kannada/dictionary/dict.ltr.txt) |
| English | english_finetuned_181h | Base | [english_finetuned_181h](https://storage.googleapis.com/vakyaansh-open-models/english/finetuned/english_finetuned_181h.pt) |  181             | [dict](https://storage.googleapis.com/vakyaansh-open-models/english/dictionary/dict.ltr.txt) |
| Marathi | hindi_pretrained_4kh | Base | [marathi_finetuned_100h](https://storage.googleapis.com/vakyaansh-open-models/marathi/finetuned/marathi_finetuned_100h.pt) |   100             | [dict](https://storage.googleapis.com/vakyaansh-open-models/marathi/dictionary/dict.ltr.txt) |
| Odia | hindi_pretrained_4kh | Base |[odia_finetuned_100h](https://storage.googleapis.com/vakyaansh-open-models/odia/finetuned/odia_finetuned_100h.pt) |   100             | [dict](https://storage.googleapis.com/vakyaansh-open-models/odia/dictionary/dict.ltr.txt) |
| Tamil | hindi_pretrained_4kh | Base |[tamil_finetuned_40h](https://storage.googleapis.com/vakyaansh-open-models/tamil/finetuned/tamil_finetuned_40h.pt) |   40             | [dict](https://storage.googleapis.com/vakyaansh-open-models/tamil/dictionary/dict.ltr.txt) |
| Telugu | hindi_pretrained_4kh | Base |[telugu_finetuned_40h](https://storage.googleapis.com/vakyaansh-open-models/telugu/finetuned/telugu_finetuned_40h.pt) |   40             | [dict](https://storage.googleapis.com/vakyaansh-open-models/telugu/dictionary/dict.ltr.txt) |
| Gujarati | hindi_pretrained_4kh | Base |[gujarati_finetuned_40h](https://storage.googleapis.com/vakyaansh-open-models/gujarati/finetuned/gujarati_finetuned_40h.pt) |   40             | [dict](https://storage.googleapis.com/vakyaansh-open-models/gujarati/dictionary/dict.ltr.txt) |


## Language Models

Data is taken from [AI For Bharat Corpus](https://indicnlp.ai4bharat.org/corpora/) but we do post processing by tokenizing and removing duplicates.

| Language | Type | Data | Sentences | Lexicon | LM |
|----|--------|---------|------|--|--------|
| Hindi | kenlm | [data](https://storage.googleapis.com/vakyaansh-open-models/hindi/lm_data/hi_processed.txt) | 13M | [lexicon](https://storage.googleapis.com/vakyaansh-open-models/hindi/lm/lexicon.lst) | [lm](https://storage.googleapis.com/vakyaansh-open-models/hindi/lm/lm.binary) |
| Kannada | kenlm | [data](https://storage.googleapis.com/vakyaansh-open-models/hindi/lm_data/hi_processed.txt) | 21M | [lexicon](https://storage.googleapis.com/vakyaansh-open-models/kannada/lm/lexicon.lst) | [lm](https://storage.googleapis.com/vakyaansh-open-models/kannada/lm/lm.binary) |
| English | kenlm | [data](https://storage.googleapis.com/vakyaansh-open-models/hindi/lm_data/hi_processed.txt) | 10M | [lexicon](https://storage.googleapis.com/vakyaansh-open-models/hindi/lm/lexicon.lst) | [lm](https://storage.googleapis.com/vakyaansh-open-models/hindi/lm/lm.binary) |
| Marathi | kenlm | [data](https://storage.googleapis.com/vakyaansh-open-models/marathi/lm_data/mr_processed.txt) | 22M | [lexicon](https://storage.googleapis.com/vakyaansh-open-models/marathi/lm/lexicon.lst) | [lm](https://storage.googleapis.com/vakyaansh-open-models/marathi/lm/lm.binary) |
| Odia | kenlm | [data](https://storage.googleapis.com/vakyaansh-open-models/odia/lm_data/od_processed.txt) | 0.36M | [lexicon](https://storage.googleapis.com/vakyaansh-open-models/odia/lm/lexicon.lst) | [lm](https://storage.googleapis.com/vakyaansh-open-models/odia/lm/lm.binary) |
| Tamil | kenlm | [data](https://storage.googleapis.com/vakyaansh-open-models/tamil/lm_data/ta_processed.txt) | 21M | [lexicon](https://storage.googleapis.com/vakyaansh-open-models/tamil/lm/lexicon.lst) | [lm](https://storage.googleapis.com/vakyaansh-open-models/tamil/lm/lm.binary) |
| Telugu | kenlm | [data](https://storage.googleapis.com/vakyaansh-open-models/telugu/lm_data/te_processed.txt) | 26M | [lexicon](https://storage.googleapis.com/vakyaansh-open-models/telugu/lm/lexicon.lst) | [lm](https://storage.googleapis.com/vakyaansh-open-models/telugu/lm/lm.binary) |
| Gujarati | kenlm | [data](https://storage.googleapis.com/vakyaansh-open-models/gujarati/lm_data/gu_processed.txt) | 30M |[lexicon](https://storage.googleapis.com/vakyaansh-open-models/gujarati/lm/lexicon.lst) | [lm](https://storage.googleapis.com/vakyaansh-open-models/gujarati/lm/lm.binary) |
