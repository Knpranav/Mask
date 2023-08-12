lowerGreen = np.array([40,100,0])
upperGreen = np.array([95,255,255])
GREEN - Median 79
	79  - 65
	69  - 52
	69 -  50 (pearl 69)
	49  - 42
	89  - 95 (Anomaly)
	59  - 50


lowerYellow = np.array([21,80,0])
upperYellow = np.array([51,255,255])
YELLOW - Median 30;  
	40,124,218 -  31,181,299
	40 - 31
	20,124,218 - 20,109,8
	49 - 36
	49 - 35(Mode)
	10,124,218


lowerOrange = np.array([10,100,150])
upperOrange = np.array([25,180,255])
ORANGE - Median 17
	10,138,254 - 15,105,24
	10 - 13 (Mode)
	
Conclusion : It can be inferred that Hue always reduces or remains unchanged. 
It can't become more than original value. 
We can trace the closet value available in the upperbound or its equal.
One case in green along was an anomaly where recorded median hue surpassed observation.
