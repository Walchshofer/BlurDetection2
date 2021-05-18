# Blur Detection

This is a **modified** version of [WillBrennan's BlurDetection2](https://github.com/WillBrennan/BlurDetection2), modified to:
1. Save blur map images (pretty & unpretty) along with json file when `--save-path` is set.
2. Drop requirement of .json extension from save path, as it also saves images now: input `--save-path` value without extension.
3. Adapt to Google Colaboratory Jupyter Notebook environment: replace `cv2.imshow()` with `google.colab.patches cv2_imshow()`.

Please see [original repository](https://github.com/WillBrennan/BlurDetection2) for details.
