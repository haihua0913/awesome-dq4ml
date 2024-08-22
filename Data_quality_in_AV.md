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
    - Accuracy: the discrepancy or deviance between the real-world value against the mapped value. How close is the observation to reality? 
    - Precision (resolution or granularity): how exact the description of the data is and is the smallest discernible unit or smallest unit represented?
    - Completeness: the degree to which the map contains all of the real-world features
    - Consistency: the degree of adherence to logical rules of data structure, attribution, and relationships
    - Currency (temporal accuracy, up-to-dateness, or freshness): the time between the creation of the map and the use of it
