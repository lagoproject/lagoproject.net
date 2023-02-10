# Detectors

## Water Cherenkov Detectors

### Cherenkov effect

While the speed of light in vacuum (c) is a constant, this speed is reduced in material, to 0.75c in water, for example. This means that particles can go through a material at a speed larger than the speed of light in that material (but always smaller than c).

When a particle goes through a medium at such a speed, it produces a cone of light just like a plane produces a supersonic bang upon crossing the speed of sound, or a boat (or a duck) produces a "V" behind him becauses it moves faster than the waves propagate.

This light was discovered by a russian physicist named Cherenkov in 1934, and is the responsible for the typical blue glow of water in nuclear reactors. It is used frequently in particle detectors, as a high energy particle going through a water volume will produce this caracteristic light.

### Photomultiplier tubes

Photomultiplier tubes (PMTs) are extremely sensitive light detectors, usually in ultraviolet and blue. A glass vacuum tube houses a photocathode, several dynodes, and an anode. Incident photons strike the photocathode covering the glass and electrons are produced by the photoelectric effect. High voltage between each dynode provoque an avalanche of secondary electrons, literally multiplying the signal. Typical gains of 106 mean a million electrons are detected on the anode for a single photon hitting the glass.

These detectors can therefore detect single photons, but would be destroyed if turned on in ambient light. They are usually used in light-tight environments, to detect minimum amounts of light.

### Water Cherenkov tanks

Water Cherenkov tanks are detectors based on the Cherenkov effect. A simple plastic (or metal, fiberglass...) tank is filled with water and closed, in order to be light-tight. Photomultipler tubes are installed inside the detector, looking at the water volume. When a particle crosses the water volume, it will emit light in a Cherenkov cone. The light is then uniformized in the water volume by diffusion on the walls of the tank (usually covered by a highly diffusive material), and finally collected on the photomultiplier tubes.

#### WCD calibration

WCD are easy to calibrate due to their particular signal response to different particles:

- Electrons usually drop all their energy in the detector, giving a signal proportionnal to their energy
- Photons usually convert into an electron-positron pair within the water volume, and then the secondaries radiate all their energy. In the end, the signal is again proportionnal to the energy of the incoming particle
- Muons on the other hand go through the detector without loosing all their energy (expect in the rare muon decay cases). The signal is then proportionnal to the track lenght in the detector, and no longer to the particle energy

Given the fact that energy distribution for electrons and photons fall off as power law, the signals from these particules in a WCD will also fall off as a power law. On the other hand, given the fact that the track length distribution for muons in a WCD is normally peaked at the height of the water volume (most muons are vertical), the signals of all muons will sum to give a kind of hump in a signal histogram. This hump is determined only by specific caracteristics of the detector (geometry, water purity...) and electronics (photomultiplier tube gain), and allows a precise calibration point.

#### WCD response to GRB

When a GRB occurs, a huge number of high energy photons reach the Earth's atmosphere. They impact the atmosphere and produce a cascade of particles. Out of all these cascades, some will be powerfull enough to provide a few particles at ground level. Of course, the higher in altitude one goes, the easier it will be for cascades to reach ground.

Most of the secondary particules of these cascades are photons (about 90%). A good property of WCD is the fact they can detect photons through their conversion in the water volume. This makes WCD good GRB detectors.

What one would expect is that WCD would see an increase in the photon flux when a GRB occurs. It is not easy to detect since there is a continuous high background of particles entering the WCD, but this is the challenge LAGO will try to overcome.
