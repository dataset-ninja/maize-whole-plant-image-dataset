Dataset **Maize Whole Plant Image** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogInMzOi8vc3VwZXJ2aXNlbHktZGF0YXNldHMvMTkwNV9NYWl6ZSBXaG9sZSBQbGFudCBJbWFnZS9tYWl6ZS13aG9sZS1wbGFudC1pbWFnZS1EYXRhc2V0TmluamEudGFyIiwgInNpZyI6ICJBdjlER3ZVMGdvVU9TbXl1S3dMeTd6VXExaGVKTkJnSnpCZXdwTzRCdmZnPSJ9?response-content-disposition=attachment%3B%20filename%3D%22maize-whole-plant-image-DatasetNinja.tar%22)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Maize Whole Plant Image', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://zenodo.org/record/1002675/files/Maize%20whole%20plant%20image%20dataset.zip?download=1).