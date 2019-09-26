#  README

## How to run
First of all to make it run faster you can enable the GPU runtime.

In order to replicate the results you must enable Google Drive in your Coolab and upload the file `expanded.txt`. Make sure tu pass your drive path in `load_data(<your_path>)` function.

## Results

The following results were obtained with the `expanded.txt` input.

|   | TP | TN | FP | FN | ACC |
|---|----|----|----|----|-----|
|**Spacy**|2572 | 0|232|463|0.78726|
|**Polyglot**|1736 | 0|181|1299|0.53980|
|**Pavlov**|2762 | 0|120|273|**_0.87543_**|


