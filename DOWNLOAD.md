Dataset **Maize Whole Plant Image** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzE5MDVfTWFpemUgV2hvbGUgUGxhbnQgSW1hZ2UvbWFpemUtd2hvbGUtcGxhbnQtaW1hZ2UtRGF0YXNldE5pbmphLnRhciIsICJzaWciOiAiTzQ3V3lPZTBFQlJraVJBTlFCWUptWFg4b0F6eGRHSXVTNlpXZk5pVjNyMD0ifQ==)

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