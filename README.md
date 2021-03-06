@mainpage yins (An simple implementation of SINS)
# introduction
Here is introduction

# history
2019/09/30 Add GNSS/INS/OD loosely kalman filter combination.

# docs 
See `yins_html_docs`, use browser to open html file.

# Abbreviation in code
 Abbre | explanation 
 ----  | ---- 
 Cnb         |\f$ C_n^b \f$, trans matrix n-axis to b-axis(the same as Qnb)
 Cnb,Qnb,Enb |trans from n-frame to b-axis(or attitude b-axis to n-axis)
 n,b,e,i,c,d |reference frame, navitaion/imu body/ecef/eci/carrier/odometer
 euler       |Euler attitude, [roll, pitch, yaw]
 g           |gps(or gnss phase center),gravity
 d           |data, or DELTA, mean difference, e.g. dv, dtheta
 theta       |angle increment
 v           |velocity
 SHF         |Spherical Harmonics Function
 dbl         |double
 enu,ned     |East, North, Up, Down
 v3          |3D vector
 m3          |3D matrix
 _t          |data type
 att         |attitude(could express by DCM,Quat,Euler), most express as "Enb"
 mul         |multiply
 dcm,ctm     |Direct Cosine Matrix, Coordinate Transform Matrix
 w           |Omega, Rotation rate(wie_e mean \f$ w_ie^e \f$, project to e-axis)
 rv          |rotation vector
 lat         |latitude
 lon         |longitude
 hgt         |height
 pos         |position, most represent under geodetic coordinate, (lat,lon,hgt)
 xyz         |position under ECEF, Cartesian coordinate
 rad         |radius
 deg         |degree, unit
 nav         |navigtaion
 cfg         |config/configuration
 kf          |kalman filter
 od          |odometer
 sol         |solution
 ft          |filetype
 kod         |odometer scalar factor, true/output
 itg         |intergral
 ycsv        |yins csv file, a self-explain extended csv file format for yins

# Example for LATEX
you can use LATEX here:

\f$ \lambda = \alpha \f$

\f[
     \lambda = \frac{a}{b}
\f]
