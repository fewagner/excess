hvev-r1-events-eh.csv: events in the units of eh pairs
hvev-r1-efficiency-eh.csv: efficiency curve as a function of energy in the units of eh pairs
    efficiency_curve = np.loadtxt('hvev-r1-efficiency-eh.csv', delimiter=',')
    efficiency_curve[:,0] # energies [eh pairs]
    efficiency_curve[:,1] # efficiency [fractions of 1]

Exposure: 0.487 g-days
Region of interest: 0.7-9.5 eh pairs