Dataset **Broken Glass Insulator** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/z/3/go/ZRvY8gR7Z9OtGtav7gJRJj6PmlrZI6X2LkYKR9EahuGTwaCuaZA4YChaAaUrtolEjrNGD3Cq2lPhxFtX1Ejo7udfsacsaccO5ZS0VYtR4zBningrkfD4rfChyND4.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Broken Glass Insulator', dst_path='~/dtools/datasets/Broken Glass Insulator.tar')
```
The data in original format can be 🔗[downloaded here](https://github.com/phd-benel/VPMBGI/releases/tag/dataset)