# mcnWSDDN
Weakly Supervised Deep Detection Networks for MatConvNet toolbox

## Results (PASCAL VOC 2007)
|Network  | Proposals    | Box Score       | Sp. Regularizer | Flip-Train | Multi-scale-Train | Flip-Test         | Multi-scale-Test  | mAP |
|---------|------------  |:---------------:|:---------------:|:-----------------:|:-----------------:|:-----------------:|:-----------------:|:-:|
| VGG-F   | EB | x | x | x | x |  |  | 32.5 |
| VGG-F   | EB | x | x | x | x | x|  | 33.4 |
| VGG-F   | EB | x | x | x | x | x| x| 36.4 |




## Citing WSDDN
If you find the code useful, please cite:

```latex
    @inproceedings{Bilen16,
      author     = "Bilen, H. and Vedaldi, A.",
      title      = "Weakly Supervised Deep Detection Networks',
      booktitle  = "Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition',
      year       = "2016"
    }
```


### License
The analysis work performed with the program(s) must be non-proprietary work. Licensee and its contract users must be or be affiliated with an academic facility. Licensee may additionally permit individuals who are students at such academic facility to access and use the program(s). Such students will be considered contract users of licensee. The program(s) may not be used for commercial competitive analysis (such as benchmarking) or for any commercial activity, including consulting.