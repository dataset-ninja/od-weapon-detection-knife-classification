Dataset **OD-WeaponDetection: Knife Classification** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/X/b/LG/BsUMxwUsCUQY6zorQvaqIxHKJkH07jpKnDjFBJi9GVG8UGhwpK9JnzMRiNmXMzKk1JZRfaG4OyCjXvGk0MGt3JwaV7cXQc0mgPBI15dBhdkxBixTK48TXjx5MUvL.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='OD-WeaponDetection: Knife Classification', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

