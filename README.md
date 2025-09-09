# SDY-Field Galaxy Rotation Curves

This repository contains supplementary figures for the paper:

**"The SDY-Field: An Extension of the Time Tilt Field Explaining Flat Galactic Rotation Curves and Systemic Redshifts"**  
by **Shin Dongyoon (신동윤)**

---

## 📖 Background

The **SDY-Field (Shin Dongyoon Field, TTF 2.0)** extends the original **Time Tilt Field** hypothesis by introducing **spacetime contraction**.  
This allows us to reproduce flat galactic rotation curves without invoking non-baryonic dark matter.

---

## 📊 Core Equations

The modeled rotation velocity is:

$$
V_{\text{model}}^2(R) \;=\; V_{\text{bar}}^2(R) \;+\; V_{\text{SDY}}^2(R)
$$

where the baryonic term is

$$
V_{\text{bar}}^2(R) = (U_d \, V_{\text{disk}})^2 + (U_b \, V_{\text{bulge}})^2 + V_{\text{gas}}^2 ,
$$

and the SDY-Field correction is

$$
V_{\text{SDY}}(R) = V_0 \left[ 1 - \exp \!\left( -\left(\frac{R}{R_c}\right)^{\gamma_v} \right) \right].
$$

- \( U_d, U_b \): scaling parameters for disk and bulge  
- \( V_0 \): asymptotic velocity scale  
- \( R_c \): characteristic radius  
- \( \gamma_v \): shape parameter  

---

## 🛰️ Example: NGC 2403

As a representative galaxy, we show the SDY-Field fit for **NGC 2403**.  
This galaxy is often used as a benchmark case in galactic dynamics.

### Sample Data: NGC 2403 (SPARC rotmod excerpt)

| Radius R (kpc) | V_obs (km/s) | eV_obs | V_gas | V_disk | V_bulge |
|---------------:|-------------:|-------:|------:|-------:|--------:|
| 0.16           | 24.5         | 2.83   | 0.00  | 23.21  | 0.0     |
| 0.26           | 35.3         | 2.46   | 0.00  | 35.33  | 0.0     |
| 0.36           | 43.2         | 1.12   | 1.92  | 46.97  | 0.0     |
| 0.46           | 52.0         | 1.25   | 2.29  | 56.68  | 0.0     |
| 0.56           | 60.9         | 2.93   | 2.64  | 63.77  | 0.0     |
| 0.66           | 65.8         | 1.25   | 3.00  | 67.56  | 0.0     |
| 0.76           | 71.7         | 1.25   | 3.34  | 70.83  | 0.0     |
| 0.86           | 74.6         | 1.60   | 3.68  | 72.80  | 0.0     |
| 0.96           | 74.6         | 1.03   | 4.02  | 74.87  | 0.0     |
| 1.06           | 76.6         | 1.12   | 4.37  | 77.12  | 0.0     |

### Fit Function

The model curve is given by:

$$
V_{\text{fit}}(R) = \sqrt{ V_{\text{bar}}^2(R) + V_{\text{SDY}}^2(R) } .
$$

### Resulting Graph

![NGC2403 Rotation Curve](figures/NGC2403_SDY_fit_0to100kpc.png)

---

## 📂 Figures

- **Total galaxies analyzed:** 175 (SPARC rotmod dataset)  
- **Format:** PNG (rotation curve fits, radius 0–100 kpc)  

Each figure shows:
- Observed data (black points with error bars)  
- Scaled baryonic contribution (dashed line)  
- SDY-Field correction (dotted line)  
- Final combined fit (solid line)  

All figures are available in the `/figures/` folder.  

---

## 📎 Citation

If you use these figures or formulas, please cite:

