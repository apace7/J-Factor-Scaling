columns description:
weights -- weight of each chain.  Needs to be used for any statistic computed
vel_avr -- average velocity (km/s) of dSph. part of chain
dist -- distance to dSph (kpc). Gaussian prior.
ellipticity -- ellipticity of dSph. Gaussian prior. For some objects this is fixed to 0 and not included.
rplummer -- plummer radius (arcmin).  Gaussian prior
rs -- log10(rs/kpc). Scale radius of NFW profile
rhos -- log10(ps/(Msolar/kpc^3)). Scale density of NFW profile.
beta -- symmetrized anisotropy parameter (see text)
logtemp -- 2 log(likelihood) 
jfac_0d01 -- log10 of  J-factor (0.01 degree) in Msolar^2/kpc^5
jfac_0d1 -- log10 of  J-factor (0.1 degree) in Msolar^2/kpc^5
jfac_0d15 -- log10 of  J-factor (0.15 degree) in Msolar^2/kpc^5
jfac_0d2 -- log10 of  J-factor (0.2 degree) in Msolar^2/kpc^5
jfac_0d3 -- log10 of  J-factor (0.3 degree) in Msolar^2/kpc^5
jfac_0d5 -- log10 of  J-factor (0.5 degree) in Msolar^2/kpc^5
jfac_1d0 -- log10 of  J-factor (1.0 degree) in Msolar^2/kpc^5
dfac_0d1 -- log10 of  D-factor (0.1 degree) in Msolar/kpc^2
dfac_0d2 -- log10 of  D-factor (0.2 degree) in Msolar/kpc^2
dfac_0d5 -- log10 of  D-factor (0.5 degree) in Msolar/kpc^2
rtidal -- tidal radius (kpc) used for J/D calculation.

(note that these chains don't have ac J and D factor.

The units in the plots are (_corner):
mean velocity (overline{v}, km/s)
distance (d, kpc)
ellipticity (\epsilon, some objects have ellipticity fixed to zero)
plummer radius (r_h, arcmin)
log10 of r_s (\log_{10}{r_s}, r_s is in kpc)
log10 of rho_s (\log_{10}{\rho_s}, r_s is in M_solar/kpc^3)
azimuthally average anisotropy (\tilde\beta), see paper for details)

plots (_jfac_corner)
distance (d, kpc)
half-light radius (r_{1/2}, parsec)
log10 of r_s (\log_{10}{r_s}, r_s is in kpc)
log10 of rho_s (\log_{10}{\rho_s}, r_s is in M_solar/kpc^3)
azimuthally average anisotropy (\tilde\beta), see paper for details)
log_10 J-factor (0.1 deg, GeV^2 cm^{-5} )
log_10 J-factor (0.5 deg, GeV^2 cm^{-5} )
log_10 D-factor (0.5 deg, GeV cm^{-2} )
