# ICTC 1D (tubo–carcasa) con ebullición interna – Contracorriente

Modela un intercambiador **tubo–carcasa** 1D para evaporación y sobrecalentamiento de agua usando **sal solar** como fluido caliente. Tres zonas: I (líquido), II (ebullición) con **Gungor–Winterton (1987)** y III (vapor). Lado carcasa con **Kern**, tubo monofásico con **Gnielinski**. Número de tubos desde **Incropera** (1" OD, 1.25" pitch, 1-P).

## Contenido
- `ICTC_1D_contracorriente.ipynb` – notebook principal
- `requirements.txt` / `environment.yml` – dependencias

## Cómo ejecutar
```bash
conda env create -f environment.yml
conda activate ictc-1d
jupyter lab
