## 📊 Experimental Results and Visualizations

The following figures were exported from the original Jupyter notebook. They document the NASA IMS Bearing Run 2 experimental pipeline.

### Raw Vibration Signals
![Raw vibration signals](images/01_raw_vibration_signals.png)

### RMS and Kurtosis Trends
![RMS and kurtosis trends](images/02_rms_kurtosis_trends.png)

### Autoencoder Training and Validation Loss
![Autoencoder training loss](images/03_autoencoder_training_loss.png)

### Health Indicator Evolution
![Health indicator evolution](images/04_health_indicator_evolution.png)

### Preliminary Alarm Threshold (Exploratory Analysis)
![Preliminary alarm threshold](images/05_preliminary_alarm_threshold.png)

**Note:** This exploratory threshold figure uses an earlier threshold configuration and should not be confused with the final alarm-threshold analysis.

### Final Bearing Degradation Curve
![Bearing degradation curve](images/06_final_degradation_curve.png)

### Industrial Monitoring Simulation
![Industrial monitoring simulation](images/07_industrial_monitoring_simulation.png)

**Evaluation note:** The report describes an alarm at index 474, approximately 84.7 hours before the end of the recorded run. The notebook explicitly uses index 474 in final visualization code; independently confirming the first automatically generated alarm requires reproducing the alert calculation. These plots come from one NASA IMS experimental run and do not establish performance across different machines.
