# Panoramic Dataset

* This database contains 1541 annotated panoramic images of work meetings at LINAGORA.

* In addition, this database contains annotations of people.

* The database note format is [VocPascal](https://medium.com/towards-artificial-intelligence/understanding-coco-and-pascal-voc-annotations-for-object-detection-bb8ffbbb36e3)

* Our repository is made up of the following files:

```
.
├── data_person

│   ├── Annotations

│   ├── ImageSets

│   │   └── Main

│   └── JPEGImages
```

All labels are annotated by [LabelImage](https://github.com/tzutalin/labelImg)

* The `Annotations` : The VOC format `.xml` for Object Detection, automatically generate by the label tools. Below is an example of `.xml` file.

 ```xml
 <annotation>
	<folder>data</folder>
	<filename>frame0.jpg</filename>
	<path>/home/ons/conf_data/data/frame0.jpg</path>
	<source>
		<database>Unknown</database>
	</source>
	<size>
		<width>1280</width>
		<height>640</height>
		<depth>3</depth>
	</size>
	<segmented>0</segmented>
	<object>
		<name>person</name>
		<pose>Unspecified</pose>
		<truncated>0</truncated>
		<difficult>0</difficult>
		<bndbox>
			<xmin>425</xmin>
			<ymin>258</ymin>
			<xmax>560</xmax>
			<ymax>443</ymax>
		</bndbox>
	</object>
	<object>
		<name>person</name>
		<pose>Unspecified</pose>
		<truncated>0</truncated>
		<difficult>0</difficult>
		<bndbox>
			<xmin>726</xmin>
			<ymin>252</ymin>
			<xmax>857</xmax>
			<ymax>432</ymax>
		</bndbox>
	</object>
	<object>
		<name>person</name>
		<pose>Unspecified</pose>
		<truncated>0</truncated>
		<difficult>0</difficult>
		<bndbox>
			<xmin>870</xmin>
			<ymin>256</ymin>
			<xmax>1048</xmax>
			<ymax>492</ymax>
		</bndbox>
	</object>
	<object>
		<name>person</name>
		<pose>Unspecified</pose>
		<truncated>0</truncated>
		<difficult>0</difficult>
		<bndbox>
			<xmin>1072</xmin>
			<ymin>278</ymin>
			<xmax>1190</xmax>
			<ymax>435</ymax>
		</bndbox>
	</object>
	<object>
		<name>person</name>
		<pose>Unspecified</pose>
		<truncated>0</truncated>
		<difficult>0</difficult>
		<bndbox>
			<xmin>246</xmin>
			<ymin>292</ymin>
			<xmax>388</xmax>
			<ymax>446</ymax>
		</bndbox>
	</object>
	<object>
		<name>person</name>
		<pose>Unspecified</pose>
		<truncated>0</truncated>
		<difficult>0</difficult>
		<bndbox>
			<xmin>68</xmin>
			<ymin>273</ymin>
			<xmax>219</xmax>
			<ymax>440</ymax>
		</bndbox>
	</object>
 </annotation>
 ```
