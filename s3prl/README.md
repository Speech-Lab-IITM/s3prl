In this repository some changes have been done for weighted sum, ensemble method and transformer encoder layers. <br />

**How to use:**

**1.** To use **Transformer Encoder layers** as a downstream task instead of Bi-directional LSTM.

```bash
python run_downstream.py -n ExpName -m train -u fbank -d asr -c downstream/asr/config_encoder.yaml
```
