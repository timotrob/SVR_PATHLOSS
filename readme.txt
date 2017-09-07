A Proposal for Path Loss Prediction in Urban Environments using Support Vector Regression

In this repository you can find the database used in the paper: A Proposal for Path Loss Prediction in Urban Environments using Support Vector Regression

The database is relative to measurements performed on four Base Station (GSM network).
 The files are linked by the field BTS_ID. Below are the fields description:

1) BTSs_Data.csv

name : BTS name
height: BTS height
lat: BTS Latitude
lon: BTS Longitude
elev: Terrain elevation
band : GSM Band
bcch: Control Channel
antenna: Antenna Model
azimuth: Antenna Azimuth
eirp: Equivalent isotropically radiated power (BTS power)
tiltEle: Electrical Tilt Angle
tiltMec: Mechanical Tilt Angle
2)Measurements.csv

lat: measurement Latitude
lon: measurement Longitude
elev: Terrain elevation
dist: Distance from BTS (Km)
horAngle: Horzontal Angle (relative to BTS)
vertAngle: Vertical Angle (relative to BTS)
PLhata : Path loss predict by Okumura-Hata model (dB)
attVer: Vertical attenuation predicted by the radiation pattern of the antenna (dB)
attHor: Horizontal attenuation predicted by the radiation pattern of the antenna (dB)
PLreal: Real loss measured (Transmitted - Received) (dB)

https://www.thinkmind.org/download.php?articleid=aict_2014_5_30_10099