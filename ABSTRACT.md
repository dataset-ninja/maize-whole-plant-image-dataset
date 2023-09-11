The authors of the **Maize Whole Plant Image Dataset** mentioned the significance of silks in maize, emphasizing their role in pollen collection and grain number determination, particularly under water deficit conditions. They noted that while silk growth is crucial for drought tolerance in maize, phenotyping it efficiently for genetic analyses is challenging.

The authors presented a reproducible pipeline they had developed for tracking ear and silk growth in hundreds of plants daily. This pipeline relied on an ear detection algorithm, which controlled a robotic camera for capturing detailed images of ears and silks. They detailed the six steps involved in the pipeline:

In step 1, the authors acquired RGB color images of each plant from multiple views daily using the PHENOARCH platform.

Step 2 involved image segmentation, where plant pixels were separated from the background using a combination of threshold algorithms.

<img src="https://github.com/supervisely/supervisely/assets/78355358/6c71b8bb-efc2-4619-bc7a-0202278c05c9" alt="image" width="800">

In step 3, they selected side view images that contained the most information for detecting ear position, considering the visibility of the stem and ear relative to the leaves.

Step 4 focused on the detection of the most probable ear position in the selected side view images, taking into account variations in stem internode width around the ear.

Step 5 explained the process of moving a camera close to the ear once it was detected, involving two imaging cabins and the conversion of pixel positions into [x, y, z] coordinates.

Finally, in step 6, the authors analyzed the images of ears and silks using two different methods, extracting relevant pixel information and computing the time courses of silk growth.

<i>Please note, that authors provided an additional 'segmentationdata.csv' file in original data with detailed info such as date, angle, height, sowing, etc.</i>
