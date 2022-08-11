# IOTstackImagery

A convenient store for imagery associated with [SensorsIot/IOTstack](https://github.com/SensorsIot/IOTstack) documentation.

Not intended to cover **all** IOTstack imagery. In general, imagery that is a simple screen shot is omitted.

Primarily intended for imagery where the master is a vector drawing, or which is assembled from components, or both.

The general structure is:

```
container/
└── container-hyphenated-description
    ├── container-hyphenated-description.ext1
    ├── container-hyphenated-description.ext2
    ├── …
    └── container-hyphenated-description.extn
```

Where:

* `container` is the Docker container the imagery is associated with; and
* `container-hyphenated-description` is the name of the final image in:

	- [IOTstack/docs/Containers/images](https://github.com/SensorsIot/IOTstack/tree/master/docs/Containers/images) 

Common extensions are:

* `.xlsx` - Microsoft Excel - input component
* `.pages` - Apple Pages - input component
* `.afdesign` - Affinity Designer - assembly, vector artwork & crop
* `.pdf` - output from `.afdesign`
* `.jpeg` and `.png` - rasterised results

`rasterise.sh` calls a custom PDF-to-target-format renderer but the same job can be done in any application like Photoshop, Affinity Photo, GIMP, etc.

