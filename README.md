# AutoEncoders for Event Detection (AEED)

## Summary
This repository contains the code used for the following publication: 
Taormina, R. and Galelli, S., 2018. Deep-Learning Approach to the Detection and Localization of Cyber-Physical Attacks on Water Distribution Systems. Journal of Water Resources Planning and Management, 144(10), p.04018065.

Although the usage is demonstrated for sensor anomalies engendered by cyber attacks on water distribution systems, the methodology could be applied for any network of sensors monitoring a physical process. AEED work by spotting incongruences in the physical relationships and spatial correlation present the recorded readings.

If you use the package, please make sure to cite the aformentioned paper, which also reports all the necessary details regarding the methodology.

## Contents

aeed.py               Python module containing the Autoencoder's Class.
aeed_batadal.ipynb    Python notebook demonstrating AEED usage for the problem described in the aformentioned publication.
./data/               Data repository on cyber-attack scenarios on WDS, also available at www.batadal.net .

