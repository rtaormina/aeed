# AutoEncoders for Event Detection (AEED): a Keras-based class for anomaly detection in water sensor networks.

## Summary
This repository contains the code used for the following publication: <br/>
***Taormina, R. and Galelli, S., 2018. Deep-Learning Approach to the Detection and Localization of Cyber-Physical Attacks on Water Distribution Systems. Journal of Water Resources Planning and Management, 144(10), p.04018065.***

Although the usage is demonstrated for sensor anomalies engendered by cyber attacks on water distribution systems, the methodology could be applied for any network of sensors monitoring a physical process. AEED work by spotting incongruences in the physical relationships and spatial correlation present the recorded readings.

If you use the package, please make sure to cite the aformentioned paper, which reports all the details on the methodology.

## Contents

* aeed.py &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Python module containing the Autoencoder's Class.
* aeed_batadal.ipynb &nbsp;&nbsp;&nbsp;Python notebook demonstrating AEED usage for the problem described in the publication.
* ./data/ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Data repository on cyber-attack scenarios on WDS, also available at www.batadal.net .

