In this repository some changes have been done for weighted sum, ensemble method and transformer encoder layers. <br />

**How to use:**

**1.** To use **Transformer Encoder layers** as a downstream task instead of Bi-directional LSTM.

```bash
python run_downstream.py -n ExpName -m train -u fbank -d asr -c downstream/asr/config_encoder.yaml
```
**2.** To do the weighted sum of multiple layers: 

```bash
python run_downstream.py -n ExpName -m train -u wavlm -d asr -lc  7 6 8
```
Here the number of layers for weighted sum can be varied instead of just 3.

**3.** To do the ensemble of weighted sum:
