## CNN Model

We have given 3 files:

1. The iPython/Jupyter notebook file (`type-Ia-supernova-classifier-cnn.ipynb`)
2. The .py file outputted from iPython/Jupyter (`type-Ia-supernova-classifier-cnn.py`)
3. Functions that are used in the other 2 files (`space_utils.py`)

For this specific model, we strongly recommend the iPython/Jupyter notebook file. The code
explanation is a lot nicer in the notebook interface, it will be easier to learn what is going on!

There are 2 main data files that are used in the code:

1. all_object_data_in_dictionary_format.pkl
2. normalized_image_object_data_in_numpy_format.pkl

The descriptions for what each one does it in the code.

However, there are 3 different sizes of each with the links below:

| Filename                                                     | S3 Link                                                                                                      | File Size |
|--------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|-----------|
| all_object_data_in_dictionary_format.pkl                     | https://s3.amazonaws.com/space2vec-public/post3/all_object_data_in_dictionary_format.pkl                     | 6.7GB     |
| normalized_image_object_data_in_numpy_format.pkl             | https://s3.amazonaws.com/space2vec-public/post3/normalized_image_object_data_in_numpy_format.pkl             | 13.0GB    |
| small_all_object_data_in_dictionary_format.pkl               | https://s3.amazonaws.com/space2vec-public/post3/small_all_object_data_in_dictionary_format.pkl               | 772.0MB   |
| small_normalized_image_object_data_in_numpy_format.pkl       | https://s3.amazonaws.com/space2vec-public/post3/small_normalized_image_object_data_in_numpy_format.pkl       | 1.5GB     |
| extra_small_all_object_data_in_dictionary_format.pkl         | https://s3.amazonaws.com/space2vec-public/post3/extra_small_all_object_data_in_dictionary_format.pkl         | 386.0MB   |
| extra_small_normalized_image_object_data_in_numpy_format.pkl | https://s3.amazonaws.com/space2vec-public/post3/extra_small_normalized_image_object_data_in_numpy_format.pkl | 744.2MB   |

You can pick any of the links from that table and use `wget <link>` to download the data.

## License
```
Copyright 2015-2020 Square, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

© 2020 Square, Inc. ATLAS, DESSA, the Dessa Logo, and others are trademarks of Square, Inc. All third party names and trademarks are properties of their respective owners and are used for identification purposes only.