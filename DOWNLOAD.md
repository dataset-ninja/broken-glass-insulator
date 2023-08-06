Dataset **VPMBGI** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/5/2/xa/TeEtJpnhEc8ZsNjFTSWPZk7SDj1f2RKGBV3i3VKdl43ZjTruIZ4R0CfTV84WmqZ0ZlY1MHxJFZn1O4hJEpkOlEPz9miTQFAHsbYkdsGBzzBq72O64TV3FdW7rLQa.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='VPMBGI', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://github.com/phd-benel/VPMBGI/releases/download/dataset/iraset.v1i.yolov7pytorch.1.zip)