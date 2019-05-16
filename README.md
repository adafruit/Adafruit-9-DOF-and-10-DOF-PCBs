# PCB for the Adafruit 9-DOF and 10-DOF Breakout boards

<a href="http://www.adafruit.com/products/512"><img src="assets/image.jpg?raw=true" width="500px"></a>

__Format is EagleCAD schematic and board layout__


* [Adafruit 9-DOF IMU Breakout - L3GD20H + LSM303](https://www.adafruit.com/product/1714)
* [Adafruit 10-DOF IMU Breakout - L3GD20H + LSM303 + BMP180](https://www.adafruit.com/product/1604)

This inertial-measurement-unit combines 2 of the best quality sensors available on the market to give you 9 axes of data: 3 axes of accelerometer data, 3 axes gyroscopic, and 3 axes magnetic (compass). We tested many different 'combination' sensors and found these were the best value, with stable and reliable readings.

The L3DG20H gyroscope + LSM303DLHC accelerometer/compass sensors are all on one breakout here, to save you space and money. Since all of them use I2C, you can communicate with all of them using only two wires. Most customers will be pretty happy with just the plain I2C interfacing, but we also break out the 'data ready' and 'interrupt' pins, so advanced users can interface with if they choose. A 3V regulator with reverse-polarity protection means you don't have to worry about frying the boards by accident. There's level shifting circuitry so the IMU can be used with 3 or 5V logic boards. And check out those mounting holes! You can securely attach this board to your rocket, robot, art project.

Each order comes with one assembled and tested 9DOF breakout board and a small piece of header.

Since this is a combination of 2 different breakouts, we suggest visiting those pages for much more information: [L3GD20H](http://www.adafruit.com/products/1032) and the [LSM303](http://www.adafruit.com/products/1120), but here are some quick stats:

- L3GD20H 3-axis gyroscope: ?250, ?500, or ?2000 degree-per-second scale
- LSM303 3-axis compass: ?1.3 to ?8.1 gauss magnetic field scale
- LSM303 3-axis accelerometer: ?2g/?4g/?8g/?16g selectable scale

[Our tutorial for this board is over on learn, including example Arduino code that will auto-calculate tilt & heading](http://learn.adafruit.com/adafruit-9-dof-imu-breakout).

## License

Adafruit invests time and resources providing this open source design, 
please support Adafruit and open-source hardware by purchasing 
products from Adafruit!

Designed by Adafruit Industries.  
Creative Commons Attribution, Share-Alike license, check license.txt for more information
All text above must be included in any redistribution

