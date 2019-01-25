# Data-from-Rio-Hotel

The two folders (i.e., "Rio_Asus" and "Rio_Samsung") consists of BLE beacon's data collected in Rio Hotel, Macau, from June 12-15, 2017.
There were three beacons deployed inside a room. We registered the fingerprint at 7 different zones, these zones are selected according to its social nature. The placement of each beacon and the zones are shown in the floorplan below.

Two devices were used to collect the data: "Rio_Asus" consists of the data collected with Asus Phone (Android 6.0), and "Rio_Samsung" consists of the data collected with Samsung Tablet (Android 7.0).
Each folder consists of 7 files (in .csv format). Each filename is named according to the following convention: "Rio_beacon_shXX". The last two digits "XX" is used to indicate the 7 zones inside a room (Please refer to the floorplan for the location of each zone).
Each dataset consists of 10 columns, the first row describes the attributes of each column.


<p align="center">
  <img alt="Tailored software services including concept, design, development and testing" src="/floorplan.png" />
</p>


## Organized Dataset
We consolidated the data obtained from both devices and further reorganize them into training and testing sample. The training dataset consists of 70k training samples, whereas the testing dataset consists of 28k samples. The "trainingLabel.csv" and "testingLabel.csv" indicate the zone of each sample.

The figure below shows all the training samples in 3D plot.

<p align="center">
  <img alt="Tailored software services including concept, design, development and testing" src="/dataset/viz/allTrainingData.png" />
</p>
