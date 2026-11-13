<div align="center">

<h1>SPARK</h1>

<p><strong>Sim-ready Part-level Articulated Reconstruction<br>with VLM Knowledge</strong></p>

<p>CVPR 2026 · <strong>Oral</strong></p>

<p>
  <a href="https://heyumeng.com/SPARK-web/"><strong>Website</strong></a> &nbsp;·&nbsp;
  <a href="https://arxiv.org/abs/2512.01629"><strong>Paper</strong></a> &nbsp;·&nbsp;
  <a href="https://github.com/YumengHe/SPARK"><strong>Code</strong></a> &nbsp;·&nbsp;
  <a href="https://huggingface.co/2bidoubi/SPARK"><strong>Model</strong></a>
</p>

<img src="static/images/SPARK_teaser.png" alt="A scene of articulated objects reconstructed with SPARK" width="900">

</div>

SPARK reconstructs simulation-ready articulated 3D objects from a single image.

Source for the SPARK project website. For reconstruction code and setup, see the [implementation repository](https://github.com/YumengHe/SPARK).

## Local preview

From this repository, run:

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

Open [localhost:8000](http://127.0.0.1:8000/). No build step is needed.

## Citation

```bibtex
@misc{he2025spark,
  title={SPARK: Sim-ready Part-level Articulated Reconstruction with VLM Knowledge},
  author={Yumeng He and Ying Jiang and Jiayin Lu and Yin Yang and Chenfanfu Jiang},
  year={2025},
  eprint={2512.01629},
  url={https://arxiv.org/abs/2512.01629}
}
```

[MIT License](LICENSE)
