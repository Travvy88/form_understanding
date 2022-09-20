# Form Understanding
## Models
### 1. LayoutLM
- Статья [LayoutLM](https://arxiv.org/abs/1912.13318)
- [Overview](https://huggingface.co/docs/transformers/model_doc/layoutlm#layoutlm) :hugging:
- GitHub [LayoutLM](https://github.com/microsoft/unilm/tree/master/layoutlm)

### 2. LayoutLMv2
- Статья [LayoutLMv2](https://arxiv.org/abs/2012.14740)
- [Overview](https://huggingface.co/docs/transformers/model_doc/layoutlmv2#layoutlmv2) :hugging:
- [Inference](https://github.com/NielsRogge/Transformers-Tutorials/blob/master/LayoutLMv2/FUNSD/Inference_with_LayoutLMv2ForTokenClassification.ipynb) & [Fine-Tuning](https://github.com/NielsRogge/Transformers-Tutorials/blob/master/LayoutLMv2/FUNSD/Fine_tuning_LayoutLMv2ForTokenClassification_on_FUNSD.ipynb) examples

#### 2.1 Tokenizer
- [PreTrainedTokenizerFast](https://huggingface.co/docs/transformers/v4.22.1/en/main_classes/tokenizer#transformers.PreTrainedTokenizerFast) :hugging: (Base class for all fast tokenizers)
- [PreTrainedTokenizerBase](https://huggingface.co/docs/transformers/v4.22.1/en/internal/tokenization_utils#transformers.PreTrainedTokenizerBase) :hugging: (Base class for PreTrainedTokenizerFast)
- Use tokenizers from :hugging: Tokenizers [guide](https://huggingface.co/docs/transformers/v4.22.1/en/fast_tokenizers)
- Tokenizers library features [quicktour](https://huggingface.co/docs/tokenizers/quicktour#quicktour) :hugging: 
- [Summary](https://huggingface.co/docs/transformers/tokenizer_summary#summary-of-the-tokenizers) of the tokenizers :hugging:
- [layoutlmv2-base-uncased](https://huggingface.co/microsoft/layoutlmv2-base-uncased/tree/main)

## Datasets
### FUNSD
- Статья [FUNSD](https://arxiv.org/pdf/1905.13538.pdf)
- [Download](https://guillaumejaume.github.io/FUNSD/download/)
- [funsd.py](https://huggingface.co/datasets/nielsr/funsd/blob/main/funsd.py)

## .ipynb
### ```funsd_vis.ipynb``` - визуализация аннотаций из датасета FUNSD
### ```layoutlmv2_inf``` - инференс модели с использованием OCR
### ```wikitext``` - просмотр содержимого датасета для обучения tokenizer
### ```tokenizer_rus``` - извлечение текста из документов и обучение tokenizer
