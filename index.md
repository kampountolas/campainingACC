# Welcome to campainingACC project

**campaigningACC** is a collaborative research project between the [University of Thessaly (UTH)](https://www.uth.gr/en) (represented by the [Automatic Control and Autonomous Systems Laboratory](http://control.mie.uth.gr/)) and [ETH Zürich](https://www.ethz.ch) (represented by the [Institute for Transport Planning and Systems](https://www.ivt.ethz.ch)). The project is supported by the [Center of Research, Innovation and Excellence (CRIE)](https://www.uth.gr/en/research/units/center-research-innovation-and-excellence-crie) of the [University of Thessaly](https://www.uth.gr/en).

The following people are currently involved in the project:
1. [Konstantinos Ampountolas](http://mie.uth.gr/Ampountolas.html) (Associate Professor, Department of Mechanical Engineering, UTH)
2. [Anastastios Kouvelas](http://www.ivt.ethz.ch/en/people/profile.anastasios-kouvelas.html) (Director, Traffic Engineering and Control, IVT, ETH Zürich)
3. [Michail Makridis](https://www.michailmakridis.com/) (Deputy Director and Senior Research Scientist, Traffic Engineering and Control, IVT, ETH Zürich)
4. Theocharis Apostolakis (PhD candidate at UTH)

## Background
Connected and automated vehicles (CAVs) promise to significantly improve road traffic. Connectivity and automation will come in different [deployment levels](https://www.aptiv.com/en/insights/article/what-are-the-levels-of-automated-driving) and the penetration rate of such vehicles on public roads is limited but constantly increasing. More specifically, most commercial vehicles sold today are equipped with [Advanced Driver Assistance Systems (ADAS)](https://en.wikipedia.org/wiki/Advanced_driver-assistance_systems) such as the [Adaptive Cruise Control (ACC)](https://en.wikipedia.org/wiki/Adaptive_cruise_control) or [Lane Keeping Assist System (LKAS)](https://www.hondainfocenter.com/2021/CR-V/Feature-Guide/Interior-Features/Lane-Keeping-Assist-System-LKAS/) that control the longitudinal and lateral position of the vehicle. Some vehicles already offer [autopilot](https://www.tesla.com/autopilot) functionalities mainly for motorways and soon for urban environments. Such systems are widely considered as predecessors of future fully autonomous driving systems. Their penetration rate in the fleet is constantly increasing, as well as their use, especially under freeway conditions. At the same time, limited information is openly available on how these systems operate and their differences depending on the vehicle manufacturer or model. This represents an important gap because as the number of ACC vehicles on the road increases, traffic dynamics on freeways may change accordingly, and new collective phenomena, which are only marginally known at present, could emerge.

Only a few test-campaigns had been carried out worldwide studying the ACC impacts under real-world driving conditions in quantitative terms. However, it is already apparent that they introduce new driving behaviors and patterns in comparison to human drivers. In many cases, such behavior may in fact bring downsides on the level of service in future road transport systems, due to relatively high reaction times, string instability, and high energy consumption under non-equilibrium conditions. 

The project campaigningACC will attempt to identify commonalities and differences between human driving behaviors and novels ones introduced by partially automated vehicles. This campaign will attempt to collect data primarily for human drivers. ACC-driven data are also welcome in case the specifications of the vehicle allow it.

## Record, save, and upload vehicle trajectory data

The application that is used to collect data is called [Phyphox](https://phyphox.org) and you can download it free of charge from the following links depending on the operation system of your mobile phone:
- **Android users:** [https://play.google.com/store/apps/details?id=de.rwth_aachen.phyphox](https://play.google.com/store/apps/details?id=de.rwth_aachen.phyphox)
- **iOS users:** [https://apps.apple.com/us/app/phyphox/id1127319693?l=de&ls=1](https://apps.apple.com/us/app/phyphox/id1127319693?l=de&ls=1)

Phyphox is a free-to-use collection of tools that exploits the sensors present in the mobile phone in order to conduct physical experiments. Common sensors available in recent mobile phones are accelererometers, gyroscopes, GPS signal, magnetometers and others. Depending on the description of the experiment, the user can select to record only the sensors that are needed for the specific experiment.

> **Caution:** It is important to select the **minimum number of sensors** because the more sensors are used the lower the data recording frequency will be.

Check out our [documentation]() that describes in detail the necessary steps to record, save and upload vehicle trajectory data to the system. 

## Publications
The following are peer-reviewed publications resulting from the project: 
* Apostolakis, Th., Makridis, M., Kouvelas, A., Ampountolas, K., __Commercially implemented adaptive cruise control systems are not evil__, *102nd Annual Meeting of the Transportation Research Board (TRB 2023)*, Jan. 8-12, 2023, Washington, DC, USA.
* Apostolakis, Th., Makridis, M., Kouvelas, A., Ampountolas, K., __Energy-based assessment of commercial adaptive cruise control systems__, in *Transportation Systems Technology and Integrated Management*, R. K. Upadhyay, S. K. Sharma, V. Kumar, and H. Valera, Eds. London, UK: Springer Nature, 2023. DOI: [10.1007/978-981-99-1517-0_4](https://www.doi.org/10.1007/978-981-99-1517-0_4).
* Ampountolas, K., __The unscented Kalman filter for nonlinear parameter identification of adaptive cruise control systems__, *IEEE Transactions on Intelligent Vehicles*, Accepted, 2023. DOI: [10.1109/TIV.2023.3272660](https://www.doi.org/10.1109/TIV.2023.3272660)
* Apostolakis, Th., Makridis, M., Kouvelas, A., Ampountolas, K., __Energy-based assessment and driving behavior of ACC systems and humans inside platoons__, IEEE Transactions on Intelligent Transportation Systems, under review, 2023.

## Support or Contact

Having trouble with sending your data? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
