# Notes

Two conda environments:

```sh
conda activate cpmf # following the OG init.sh pip reqs
```

```sh
conda activate cpmf-modern # no pip version reqs
```

```sh
python main.py --category  bagel --n-views 27 --no-fpfh False --data-path ../datasets/mvtec_3d_multiview --exp-name jul18trial --backbone resnet18
```
