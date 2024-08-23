# Autonomous Vehicles (AVs)
Alternative names: Driverless Cars, Automated Vehicles, Autonomous Driving, Self-Driving, Robotic Cars, Unmanned Vehicles, Unmanned Vehicles

# Papers

1.  [S. Li, Y. Fan, Y. Ma and Y. Pan, "Evaluation of Dataset Distribution and Label Quality for Autonomous Driving System,"
2021 IEEE 21st International Conference on Software Quality, Reliability and Security Companion (QRS-C), Hainan, China, 2021, pp. 196-200, doi: 10.1109/QRS-C55045.2021.00037.](https://ieeexplore.ieee.org/abstract/document/9742177)
- They discussed two main aspects of datasets in ADS:
    - Dataset distribution: how one specific feature impacts the accuracy of the model
    - Dataset quality: Missing label, Duplicate label, Inconsistent label
- Datasets used: Cityscapes and BDD100K

2. [K. Wong, Y. Gu and S. Kamijo, "Mapping for Autonomous Driving: Opportunities and Challenges," in IEEE Intelligent Transportation Systems Magazine, vol. 13, no. 1, pp. 91-106, Spring 2021, doi: 10.1109/MITS.2020.3014152.
](https://ieeexplore.ieee.org/abstract/document/9211790)
- Data Requirements for Autonomous Driving
    - Centimeter-level accuracy, storage efficiency, and usability ([Gwon et al.](https://ieeexplore.ieee.org/document/7420749/definitions?ctx=definitions))
    - The driving context/drivable area matters
- Five key components to data quality for autonomous driving maps:
    - Accuracy: the discrepancy or deviance between the real-world value and the mapped value. How close is the observation to reality? 
    - Precision (resolution or granularity): how exact the description of the data is and is the smallest discernible unit or smallest unit represented?
    - Completeness: the degree to which the map contains all of the real-world features
    - Consistency: the degree of adherence to logical rules of data structure, attribution, and relationships
    - Currency (temporal accuracy, up-to-dateness, or freshness): the time between the creation of the map and the use of it

3. [Yang, Z., Chai, Y., Anguelov, D., Zhou, Y., Sun, P., Erhan, D., ... & Kretzschmar, H. (2020). Surfelgan: Synthesizing realistic sensor data for autonomous driving. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (pp. 11118-11127).](https://arxiv.org/abs/2005.03844)
- synthesize camera data for autonomous driving simulations
- Dataset: Waymo Open Dataset (WOD)

4. [G. Ros, L. Sellart, J. Materzynska, D. Vazquez and A. M. Lopez, "The SYNTHIA Dataset: A Large Collection of Synthetic Images for Semantic Segmentation of Urban Scenes," 2016 IEEE Conference on Computer Vision and Pattern Recognition (CVPR), Las Vegas, NV, USA, 2016, pp. 3234-3243, doi: 10.1109/CVPR.2016.352.](https://ieeexplore.ieee.org/document/7780721)
- automatically generate realistic synthetic images with pixel-level annotations
- Current limitations: the amount and variety of annotated images of urban scenarios are much lower in terms of the total number of labeled pixels, number of classes, and instances
- SYNTHetic collection of Imagery and Annotations (SYNTHIA): precise pixel-level semantic annotations for 13 classes, i.e., sky, building, road, sidewalk, fence, vegetation, lane-marking, pole, car, traffic signs, pedestrians, cyclists and miscellaneous

