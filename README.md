# GaussianPlume: Interactive Atmospheric Dispersion Simulation

A browser-based simulation tool for modeling atmospheric pollutant dispersion using the **Gaussian Plume** model with real-world coordinates and parameters.

> 🛰️ Project Type: Environmental Modeling / Visualization  
> 🌐 Deployed at: [https://gaussianplume.github.io](https://gaussianplume.github.io)  
> 👨‍🔬 Author: Md Touhidul Islam (PhD, Environmental Engineering) <br>
     [Google Scholar](https://scholar.google.com/citations?user=pGEteP0AAAAJ&hl=en)</pre> </br>
      [LinkedIn](https://www.linkedin.com/in/touhid55/)

## 🔬 Overview

This tool visualizes the dispersion of pollutants emitted into the atmosphere from a point source using the **Gaussian plume equation**. The simulation runs entirely in the browser and incorporates parameters such as wind speed, direction, emission rate, and atmospheric stability.

It is useful for:
- Environmental impact analysis
- Teaching and demonstration
- Field scenario simulation

## 📦 Features

- ✅ Real-time browser-based interface (no backend needed)
- ✅ Custom input form for environmental parameters
- ✅ Dynamic URL encoding of simulation settings
- ✅ Optional background map and location targeting
- ✅ GitHub Pages-hosted, open-source frontend


## 🌐 Try it Live

👉 **[Run a simulation](https://gaussianplume.github.io)**  


## 🛠️ Parameters Used

| Parameter        | Description                        |
|------------------|------------------------------------|
| `wd`             | Wind Direction (degrees)           |
| `ws`             | Wind Speed (m/s)                   |
| `Q`              | Emission Rate (kg/s)               |
| `mw`             | Molecular Weight (g/mol)           |
| `sc`             | Stability Class (`ra`–`rf`)        |
| `lat`, `lon`     | Latitude and Longitude of source   |

## 📚 Documentation

This is a very simple and effective tool to visualize Gaussian dispersion model. It takes the value of "Q" in "g/s", which is the release rate."wd" is wind direction in degrees, "ws" is wind speed in "m/s"."mw" takes the value of Molecular Weight of released material. For example, 17.013 for ammonia."sc" is the stability class that has values for both urban and rural conditions. We considered Pasquill-Gifford Dispersion Coefficient for Plume Dispersion. For "A" to "F" stability class in both urban and rural conditions, the simulation takes the value of "sc" as ra,rb,rc,....upto rf or ua,ub,uc....upto uf. Finally, "lat" and "lon" take the values of Latitude and Longitude.

Assumptions:
The following assumptions were used to make the simulation.

1. Steady-state conditions, which imply that the rate of emission from the point source is constant.</br>
2. Wind speed is constant both in time and with height (wind direction shear is not considered).</br>
3. Mass is conserved through reflection at surfaces.</br>
4. The model should be applied for average wind speeds of more than 1 m/s (> 1 m/s).</br>
5. The terrain underlying the plume is flat.</br>


## 💡Inspiration
<a href="https://www.epa.gov/cameo/aloha-software" target="_blank">ALOHA(Areal Location of Hazardous Atmosphere)</a> and <a href="https://www.dnvgl.com/services/process-hazard-analysis-software-phast-1675" target='_blank'>PHAST(Process Hazard Analysis Software)</a> provided the main inspiration for this project

## 📘References
1.CCPS(Center for Chemical Process Safety),2010,Guidelines for Chemical Process Quantitative Risk Analysis,A JOHN WILEY & SONS, INC., PUBUCATION, Chap. 2. ISBN:0-8169-0720-X </br>
2. Crowl D.A., and Louvar J.F., 2011, Chemical Process Safety, New Jersey: Prentice Hall, Chap. 4.
ISBN: 0-13-018176-5

## ©️License & Copyright</br>
&copy; Md Touhidul Islam, Bangladesh University of Engineering and Technology </br>
Licensed under the [MIT License](https://github.com/touhid55/GaussianPlume/blob/master/LICENSE)

## 📜 Citation
Islam, M. T. (2018). GaussianPlume: Interactive Atmospheric Dispersion Simulator (Version 2.0.0) [Computer software]. https://github.com/touhid55/GaussianPlume


## 📂 File Structure

```bash
├── index.html        # Main simulation interface
├── img/              # Optional background or visual assets
├── README.md         # Project documentation
└── CITATION.cff      # Citation file
