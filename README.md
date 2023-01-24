# SCADN

Learning Semantic Context from Normal Samples for Unsupervised Anomaly Detection
https://ojs.aaai.org/index.php/AAAI/article/view/16420

- **PSNR**
https://emjayahn.github.io/2019/09/01/psnr-ssim/

> 이미지의 화질을 평가하는 metric
_본 논문에서는 언급되어 있지 않으나 reference 코드에서는 이미지의 품질을 평가하기 위한 후처리 과정으로 사용됨_
- peak_signal_noise_ratio : 이미지의 피크 신호 대 잡음비(PSNR)를 계산
- notes : 버전 0.16의 변경 : 해당 기능에서 이름 변경
- skimage.measure.compare_psnr에 skimage.metrics.peak_signal_noise_ratio 
    * 추가 reference : https://runebook.dev/ko/docs/scikit_image/api/skimage.metrics


**Reference**
https://github.com/Xudong-Yan/SCADN.git


