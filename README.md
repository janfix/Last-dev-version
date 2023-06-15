# PCI DeLor IMS Version
<img src="https://www.wiquid.fr/projects/depp/PCI-icons/delor.svg">

## Installation 
This repository is dedicated to Delor PCI. If you want to download all DEPP-Wiquid PCIs in a row, go to [Extension-Wiquid-Depp](https://github.com/janfix/Extension-Wiquid-Depp).
If not, download the PCI, create a ZIP with the ImsPciCreator file at the root level, go to TAO platform, in the top right tool bar click on ⚙️ (settings)> Portable custom interaction and install it as a package.

## Description
Measuring the weight and volume of a statuette

## Results
This PCI is an interactive animation. It collects data to verify if and how the animation was used : 
Each interaction generate the state of the PCI : where is the statuette, what is the water volume, what indicates the scale...
The results are in JSON format.
<br/> example : [{
	"statuette_balance": false,
	"statuette_becher": false,
	"volume_eau": "",
	"valeur_balance": "" //Scale IS OFF
}, {
	"statuette_balance": false,
	"statuette_becher": false,
	"volume_eau": "",
	"valeur_balance": ""
}, {
	"statuette_balance": false,
	"statuette_becher": false,
	"volume_eau": "",
	"valeur_balance": "0 g" //Scale is ON
}, {
	"statuette_balance": false,
	"statuette_becher": true,
	"volume_eau": 0,
	"valeur_balance": "0 g"
}, {
	"statuette_balance": false,
	"statuette_becher": true,
	"volume_eau": 97,
	"valeur_balance": "0 g"
}, {
	"statuette_balance": true,
	"statuette_becher": false,
	"volume_eau": 87,
	"valeur_balance": "190 g"
}]


<img src="https://www.wiquid.fr/wp-content/uploads/2021/12/cropped-cropped-WonderP50.png" alt="Wiquid" title="Wiquid">