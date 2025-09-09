# SDY-Field-Galaxy-Rotation
“Supplementary figures for SDY-Field galaxy rotation curve analysis (175 galaxies)”
# SDY-Field Galaxy Rotation Curves

This repository contains supplementary figures for the paper:

**"The SDY-Field: An Extension of the Time Tilt Field Explaining Flat Galactic Rotation Curves and Systemic Redshifts"**  
by **Shin Dongyoon (신동윤)**

---

## 📖 Background

The **SDY-Field (Shin Dongyoon Field, TTF 2.0)** extends the original **Time Tilt Field** hypothesis by introducing **spacetime contraction**.  
This modification allows us to reproduce **flat galactic rotation curves** without invoking non-baryonic dark matter.

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

## 🚀 Usage

1. Open `/figures/` to browse individual galaxy fits.  
2. Download the full set if you want to analyze offline.  
3. These figures can be cited as supplementary material to the SDY-Field paper.

---

## 📎 Citation

If you use these figures or formulas, please cite:

