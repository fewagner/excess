hvev-r2-events-eV.csv: events [eV]
hvev-r2-efficiency-eV.csv: efficiency curve as a function of energy
    efficiency_curve = np.loadtxt('hvev-r2-efficiency-eV.csv', delimiter=',')
    efficiency_curve[:,0] # energies [eV]
    efficiency_curve[:,1] # efficiency [fractions of 1]

Exposure: 1.22 g-days
Region of interest: 50-650 eV

The spectrum can be empirically converted to the eh pair units by dividing it by 101.75 eV.
The conversion factor is obtain by fitting the neh-pair peaks with gaussians.