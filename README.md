# Measuring-the-Z-boson-mass
a sample of 𝑍 boson candidates recorded by CMS in 2011 and published at CERN opendata portal. It comes from DoubleMuon dataset with the following selection applied:

    Both muons are "global" muons
    invariant mass sits in range: 60 GeV < 𝑀𝜇𝜇 < 120 GeV
    |𝜂| < 2.1 for both muons
    𝑝𝑡 > 20 GeV

The following columns presented in the CSV file:

    Run, Event are the run and event numbers, respectively
    pt is the transverse momentum 𝑝𝑡 of the muon
    eta is the pseudorapidity of the muon: 𝜂
    phi is the 𝜙 angle of the muon direction
    Q is the charge of the muon
    dxy is the impact parameter in the transverse plane: 𝑑𝑥𝑦 - how distant is the track from the collision point
    iso is the track isolation: 𝐼𝑡𝑟𝑎𝑐𝑘 - how many other tracks are there around given track

To show the .csv file use:
  df = pd.read_csv('Zmumu.csv')
  print (df)
