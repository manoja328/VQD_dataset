# VQD_dataset

The VQD dataset zipped files contains two splits train and val in json file format. All the images used are from MSCOCO 2014 train and val split. The ground truth boxes are *in  x , y , w, h* format from top-left. Each entries in the dataset contains the following examples fields:

```
{'question': 'Where is the dining table in the image?',
 'gtbox': [[373, 459, 134, 15]],
 'question_type': 'simple',
 'question_id': 57,
 'image_id': 164,
 'width': 640,
 'height': 480,
 'file_name': 'COCO_val2014_000000000164.jpg',
 'split': 'val'}

````
The 'gtbox' field refers to the Grouth-truth bounding box in the image.
