# VQD_dataset

The VQD dataset contains two splits train and val. Each split contains the following examples fields:

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
All the field should be pretty self explanatory. The 'gtbox' field refers to the Grouth-truth bounding box in the image.
