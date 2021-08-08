## Modifications
The original Jupyter notebooks created by `NielRogge` was written to be run (presumably) on
Google Colab. I have made modifications to render them runnable in local Linux machines.
(For readers using MacOS/Windows, they might need further modify the commands in Jupyter notebook cells
to make them work on the corresponding OS.)


Major changes include

- Shell command rendered broader
- The Python package `pathlib` instead of `os`



## A Few Python Scripts Worth Reading
- `huggingface/transformers/src/transformers/models/bert/tokenization_bert.py` to better understand the class `LayoutLMTokenizer`, which is a subclass of `BertTokenizer`


