Carbendazim vs. Aspergillus flavus
An interactive, high-fidelity biological simulation exploring the molecular and macroscopic effects of the fungicide Carbendazim on the growth and toxin production of Aspergillus flavus.

This project simulates the mechanism of mitotic arrest via tubulin binding and models the emergence of fungicide resistance through stochastic mutation.

![alt text](https://img.shields.io/badge/license-MIT-blue.svg)

![alt text](https://img.shields.io/badge/tech-HTML5%20%2F%20Canvas-orange.svg)

![alt text](https://img.shields.io/badge/field-Mycology%20%2F%20Bioinformatics-green.svg)

🔬 Scientific Context

Mechanism of Action
Carbendazim is a systemic benzimidazole fungicide. Its primary mode of action is the inhibition of fungal cell division. It binds to the
β
β
-tubulin protein subunits, preventing the polymerization of microtubules. Without functioning microtubules, the fungal cell cannot move chromosomes during mitosis, leading to mitotic arrest.

The Pathogen
Aspergillus flavus is a common saprotrophic and pathogenic fungus known for contaminating agricultural crops (like chilli and maize). Its primary danger lies in the production of Aflatoxins, which are potent hepatocarcinogens.

Simulation Parameters
Optimal Dosage: 0.15% concentration yields ~73% growth inhibition.

Toxin Limit: Regulatory safety threshold is modeled at 20 ppb.

Resistance: Modeled via a 0.2% probability of mutation under selection pressure.

🚀 Features
Microscopic View: Real-time animation of microtubule assembly and chromosomal separation. Watch "shattered" tubulin filaments appear upon fungicide application.

Macroscopic Petri Dish: A Canvas-based growth engine simulating radial colony expansion on a chilli surface.

Resistance Engine: A stochastic model that allows a "Resistant" phenotype (purple) to emerge over time, resuming growth despite chemical treatment.

Real-time Analytics:

Fungal Growth (%)

Aflatoxin Concentration (ppb)

Resistance Index (%)

Dynamic Controls: Adjust fungicide concentration, simulation speed (1x to 5x), and zoom levels.

🛠️ Tech Stack
Frontend: Pure HTML5 / CSS3 (Glassmorphism UI).

Graphics: Triple-buffered HTML5 Canvas API for high-performance animations.

Logic: Vanilla JavaScript (ES6+) using requestAnimationFrame for 60fps synchronization.

Architecture: Single-file distribution for maximum portability and zero-dependency deployment.

📂 Installation & Usage
No installation or build step is required.

Clone the repository:

code
Bash
git clone https://github.com/your-username/carbendazim-asperillus-lab.git
Open index.html in any modern web browser (Chrome, Firefox, Safari, Edge).

📊 Simulation Logic
The application follows three distinct biological states:

Untreated State:

Growth: Linear radial expansion.

Toxin: Exponential accumulation relative to biomass.

Micro: Normal mitosis cycle.

Treatment Active (Control):

Tubulin binding proportional to concentration slider.

Growth slows by up to 80%.

Colony color shifts to "Inhibited Pale."

Resistance Selection:

Under treatment, there is a cumulative probability per "Day" of a mutation event.

Once triggered, the Resistance Index climbs, and growth rates begin to recover as the fungus bypasses the tubulin-binding site.

📜 License
Distributed under the MIT License. See LICENSE for more information.

🧬 Acknowledgments
This simulation was designed for educational use in mycology and agricultural science.

Based on empirical data regarding Aspergillus inhibition rates and Aflatoxin B1 production cycles.
