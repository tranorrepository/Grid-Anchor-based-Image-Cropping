# Grid-Anchor-based-Image-Cropping

#### Abstract
Image cropping aims to improve the composition as well as aesthetic quality of an image by removing extraneous content from it. Existing image cropping databases provide only one or several human-annotated bounding boxes as the groundtruth, which cannot reflect the non-uniqueness and flexibility of image cropping in practice. The employed evaluation metrics such as intersection-over-union cannot reliably reflect the real performance of cropping models, either. This work revisits the problem of image cropping, and presents a grid anchor based formulation by considering the special properties and requirements (e.g., local redundancy, content preservation, aspect ratio) of image cropping. Our formulation reduces the searching space of candidate crops from millions to less than one hundred. Consequently, a grid anchor based cropping benchmark is constructed, where all crops of each image are annotated and more reliable evaluation metrics are defined. We also design an effective and lightweight network module, which simultaneously considers the region of interest and region of discard for more accurate image cropping. Our model can stably output visually pleasing crops for images of different scenes and run at a speed of 125 FPS.

#### Material
## [Paper](https://drive.google.com/file/d/1q9jxaJEn2AhEgQEUKHOgGCPQtHRuGNO3/view?usp=sharing), [Supplementary](https://drive.google.com/open?id=154BHBSzl-C9tP-5Gvjcf6GJmNCVv6X-l), [Dataset](https://drive.google.com/open?id=1KhmyjoimsQVXqPnLjKZiU4iXNKNyyxqW), [PretrainedModel](https://drive.google.com/open?id=1OvLT_ul17zCK4ljAi4myGAgA50PmLy3Y).


#### Depedency
1. Matlab
2. [MatConvNet](http://www.vlfeat.org/matconvnet/). 


