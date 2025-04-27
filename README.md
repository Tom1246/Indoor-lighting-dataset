# Indoor-lighting-dataset
## Description
This dataset is collected from Classroom 107 in the First Teaching Building of the Medical School of Nanchang University and is used for indoor lighting model research.

## Data Format
The data is stored in mat format and includes the following fields:
- **Measured Illuminance**: Actual illuminance collected by a handheld illuminometer in the user activity area corresponding to the multimodal sensor.
- **Measured Color Temperature**: Actual color temperature collected by a handheld illuminometer in the user activity area corresponding to the multimodal sensor.
- **Recorded Illuminance**: Illuminance readings obtained by the multimodal sensor corresponding to the luminaire.
- **Recorded Color Temperature**: Color temperature readings obtained by the multimodal sensor corresponding to the luminaire.
- **Recorded Temperature**: Indoor temperature readings obtained by the multimodal sensor corresponding to the luminaire.
- **Recorded Humidity**: Indoor humidity readings obtained by the multimodal sensor corresponding to the luminaire.
- **Luminaire Voltage**
- **Luminaire Current**

## Data Collecting Method
The data is collected through multimodal sensors. In the experiment, the color temperature range is set from 2500K to 5000K, adjusted in steps of 500K; the output illuminance is adjusted in increments of 10% from 30% to 100%. Subsequently, the reflected illuminance and the operating voltage and current of the luminaires are measured by the corresponding multimodal sensors. Finally, a handheld illuminometer is used to measure and record the illuminance and color temperature of the user activity area directly below the sensor. The dataset includes five common weather conditions: sunny, rainy, foggy, cloudy, and thundershower.
