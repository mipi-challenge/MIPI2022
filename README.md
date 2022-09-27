# Mobile Intelligent Photography and Imaging Challenge (MIPI) 2022 
Dataset and Code for MIPI 2022 Challenge in ECCV 2022. [[Workshop Webpage]](https://mipi-challenge.org/)

<p align="center">
  <img src="assets/mipi-webpage.png" width="800">
</p>

## Challenge Tracks
All data and baseline code are hosted on Google Drive:
(TBD)
| Track | Dataset | Code | Report | Description
| :--- | :--: | :----: | :----: | :----------
| [RGB+ToF Depth Completion](https://codalab.lisn.upsaclay.fr/competitions/4956) | [link](https://drive.google.com/file/d/1OkuUhlv5i5EIh5y7bgYTt_5ZRGF__1aT/view?usp=sharing) | [link](https://github.com/ZHUQINGPENG/MIPI2022-RGB-ToF-depth-completion) | [link](https://arxiv.org/abs/2209.07057) | Uses sparse, noisy ToF depth measurements with RGB images to obtain a complete depth map.
| [Quad Joint Remosaic and Denoise](https://codalab.lisn.upsaclay.fr/competitions/4955) | link | link | [link](https://arxiv.org/abs/2209.07060) | Converts Quad-Bayer RAW data into Bayer format so that it can be processed with standard ISPs.
| [RGBW Joint Remosaic and Denoise](https://codalab.lisn.upsaclay.fr/competitions/4954) | link | link | [link](https://arxiv.org/abs/2209.08471) | Converts RGBW RAW data into Bayer format so that it can be processed with standard ISPs.
| [RGBW Joint Fusion and Denoise](https://codalab.lisn.upsaclay.fr/competitions/4953) | link | link | [link](https://arxiv.org/abs/2209.07530) | Fuses Bayer data and a monochrome channel data into Bayer format to increase SNR and spatial resolution.
| [Under-display Camera Image Restoration](https://codalab.lisn.upsaclay.fr/competitions/4874) | link | link | [link](https://arxiv.org/abs/2209.07052) | Improves the visual quality of image captured by a new imaging system equipped under-display camera.

## Terms and Conditions
Please check the [terms and conditions](https://mipi-challenge.org/terms.html) of MIPI for further rules for using the datasets and codes.


## Citation
If you find our dataset and code are useful for your research, please consider citing our reports:

```bibtex
@InProceedings{sun2022mipidc,
    title = {MIPI 2022 Challenge on RGB+ ToF Depth Completion: Dataset and Report},
    author = {Sun, Wenxiu and Zhu, Qingpeng and Li, Chongyi and Feng, Ruicheng and Zhou, Shangchen and Jiang, Jun and Yang, Qingyu and Loy, Chen Change and Gu, Jinwei},
    booktitle = {ECCV Workshop},
    year = {2022}
}

@InProceedings{yang2022mipiquad,
    title = {MIPI 2022 Challenge on Quad-Bayer Re-mosaic: Dataset and Report},
    author = {Yang, Qingyu and Yang, Guang and Jiang, Jun and Li, Chongyi and Feng, Ruicheng and Zhou, Shangchen and Sun, Wenxiu and Zhu, Qingpeng and Loy, Chen Change and Gu, Jinwei},
    booktitle = {ECCV Workshop},
    year = {2022}
}

@InProceedings{yang2022mipirgbwrm,
    title = {MIPI 2022 Challenge on RGBW Sensor Re-mosaic: Dataset and Report},
    author = {Yang, Qingyu and Yang, Guang and Jiang, Jun and Li, Chongyi and Feng, Ruicheng and Zhou, Shangchen and Sun, Wenxiu and Zhu, Qingpeng and Loy, Chen Change and Gu, Jinwei},
    booktitle = {ECCV Workshop},
    year = {2022}
}

@InProceedings{yang2022mipirgbwsf,
    title = {MIPI 2022 Challenge on RGBW Sensor Fusion: Dataset and Report},
    author = {Yang, Qingyu and Yang, Guang and Jiang, Jun and Li, Chongyi and Feng, Ruicheng and Zhou, Shangchen and Sun, Wenxiu and Zhu, Qingpeng and Loy, Chen Change and Gu, Jinwei},
    booktitle = {ECCV Workshop},
    year = {2022}
}

@InProceedings{feng2022mipiudc,
    title = {MIPI 2022 Challenge on Under-Display Camera Image Restoration: Methods and Results},
    author = {Feng, Ruicheng and Li, Chongyi and Zhou, Shangchen and Sun, Wenxiu and Zhu, Qingpeng and Jiang, Jun and Yang, Qingyu and Loy, Chen Change and Gu, Jinwei},
    booktitle = {ECCV Workshop},
    year = {2022}
}
```