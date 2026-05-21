Данные
В проекте используется открытый датасет Kaggle:
Ethereum Fraud Detection Dataset  
https://www.kaggle.com/datasets/vagifa/ethereum-frauddetection-dataset
Файл датасета после скачивания называется:
```text
transaction_dataset.csv
```
Его можно скачать через Kaggle API в Google Colab командой:
```python
!kaggle datasets download -d vagifa/ethereum-frauddetection-dataset -p /content/data
!unzip -o /content/data/ethereum-frauddetection-dataset.zip -d /content/data
```
Файл `kaggle.json` нельзя загружать в репозиторий, так как это личный API-ключ.