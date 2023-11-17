The principle of operation of a position and orientation inductive sensor is based on a detailed mapping of quasistatic magnetic fields induced in free space
by a set of miniature coils (or loops) called “magnetic dipoles”. Depending on the task, one, two or a maximum of three coils in the mutually orthogonal planes can be used to produce the required magnetic pattern in free space. Each coil is energised by a sinusoidal current in the kHz range or a pulse sequence: independently or with a certain phase. The quasistatic condition means that the electromagnetic wavelength in free space is much larger than any dimensions in the system, including the coil diameters and the distance between the source of magnetic field and the sensor head. Therefore, the retardation effect caused by the finite speed of light can be completely neglected. The aim is to obtain a unique vector magnetic field (time-dependent) in each coordinate point. The magnetic field in an observation point can be measured by means of a set of miniature coils (or loops) comprising the sensor head which is attached to the tracking object. The sensor head may also include one, two, or a maximum of three miniature coils in the mutually orthogonal planes. To recognise the position and orientation of the sensor head, some algorithm has to be proposed that recalculates the magnetic field pattern into the coordinates and orientation angles. 
In this project, the Kalmus’ guidance method has been successfully implemented for robot navigation. The method, first proposed by Henry Kalmus*), was originally designed to aid vehicles to follow one another. In his method, the two crossed excitation coils are fed from a low frequency source (kHz) in phase quadrature (/2-phase shift). The sensor head placed on a moving platform comprises the two crossed pickup coils and changes its azimuthal orientation with respect to the line of sight between the excitation and sensor heads. It has been shown that the orientation can be determined by measuring the phase difference between the pickup voltages. I used this principle to build a navigation system that forces the slave mobile platform (“tank”) to follow the leading platform. The leading platform is controlled using remote control and carries the transmission coils (source of quasistatic magnetic field), while the slave platform carries the pickup coils that provide information on the distance from the source of magnetic field and its angle position with respect to the slave platform. Based on a short research, this is the first use of inductive sensors for robot navigation. To adapt the Kalmus’ guidance method, modern electronic components and digital signal processing techniques has been used. 
*) H. P. Kalmus, “A New Guiding and Tracking System”, IRE Transactions on Aerospace and Navigational Electronics, Vol. 9, pp. 7–10, (1962).
