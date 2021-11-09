## What our system can do?

- bee detection,
- pollen loads detection,
- bee pose estimation,
- activity in time analysis.

## Summary of the 2021 season

### IoT

![IoT](https://github.com/PabloMaj/Computer-vision-system-for-apiary/blob/gh-pages/docs/assets/IoT_image.jpg?raw=true)

### Number of collected samples

![summary_no_samples](https://github.com/PabloMaj/Computer-vision-system-for-apiary/blob/gh-pages/docs/assets/summary_no_collected_samples.png?raw=true)

- **400k** images from 3 hive stations,
- data acquisition from **April 25 to September 15** without interruptions. 

### External conditions (temperature, humidity, pressure)

![summary_external_conditions](https://github.com/PabloMaj/Computer-vision-system-for-apiary/blob/gh-pages/docs/assets/summary_external_conditions.png?raw=true)

### Temperature of raspberry depending on external temperature

![summary_temperature_raspberry](https://github.com/PabloMaj/Computer-vision-system-for-apiary/blob/gh-pages/docs/assets/raspberry_temp_vs_external_temp.png?raw=true)

## Machine learning models

### Position and orientation of bees determination

![position_orientation](https://github.com/PabloMaj/Computer-vision-system-for-apiary/blob/gh-pages/docs/assets/midpoints_and_orientation_determination.png?raw=true)

### Probability density function for bee location

![rgb_with_midpoints](https://github.com/PabloMaj/Computer-vision-system-for-apiary/blob/gh-pages/docs/assets/RGB_with_midpoints.png?raw=true)
<br />
![rgb_with_density_map](https://github.com/PabloMaj/Computer-vision-system-for-apiary/blob/gh-pages/docs/assets/RGB_with_density_map.png?raw=true)

### Orientation of bees distribution in the area of analysis 

![rgb_with_midpoints](https://github.com/PabloMaj/Computer-vision-system-for-apiary/blob/gh-pages/docs/assets/RGB_with_orientation_distribution.png?raw=true)
<br />
![rgb_with_density_map](https://github.com/PabloMaj/Computer-vision-system-for-apiary/blob/gh-pages/docs/assets/orientation_distribution_colorbar.png?raw=true)

### Bee detection

![bee_3](https://github.com/PabloMaj/Computer-vision-system-for-apiary/blob/gh-pages/docs/assets/bee_3.jpg?raw=true)
![bee_7](https://github.com/PabloMaj/Computer-vision-system-for-apiary/blob/gh-pages/docs/assets/bee_7.jpg?raw=true)

<html>
<p float="left">
  <img src="https://github.com/PabloMaj/Computer-vision-system-for-apiary/blob/gh-pages/docs/assets/precision_recall_bee.png" width="500" raw=true/>
  <img src="https://github.com/PabloMaj/Computer-vision-system-for-apiary/blob/gh-pages/docs/assets/f1_score_confidence_bee.png" width="500" raw=true/> 
</p>
</html>
  
**Metrics**<br />
AP = 94.47% (for IoU=0.5)<br />
Working point (confidence score=0.95):<br />
F1-score=0.9205<br />
precision=0.9363<br />
recall=0.9052<br />

### Pollen loads detection

![pollen_7](https://github.com/PabloMaj/Computer-vision-system-for-apiary/blob/gh-pages/docs/assets/pollen_7.jpg?raw=true) 
![pollen_9](https://github.com/PabloMaj/Computer-vision-system-for-apiary/blob/gh-pages/docs/assets/pollen_9.jpg?raw=true)

<p float="left">
  <img src="https://github.com/PabloMaj/Computer-vision-system-for-apiary/blob/gh-pages/docs/assets/precision_recall_pollen.png" width="500" raw=true/>
  <img src="https://github.com/PabloMaj/Computer-vision-system-for-apiary/blob/gh-pages/docs/assets/f1_score_confidence_pollen.png" width="500" raw=true/> 
</p>

**Metrics**<br />
AP = 94.58% (for IoU=0.5)<br />
Working point (confidence score=0.95):<br />
F1-score=0.9388<br />
precision=0.9452<br />
recall=0.9324<br />

### Pollen loads clustering

[editor on GitHub](https://github.com/PabloMaj/Computer-vision-system-for-apiary/edit/gh-pages/index.md)

