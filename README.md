# Računalni Vid – Night Light Segmentation

Projekt koristi **računalni vid i duboko učenje** za segmentaciju noćnih svjetala na slikama.  
Implementirano u Pythonu pomoću **PyTorch**, **Segmentation Models PyTorch**, **Albumentations** i **OpenCV**.

---

## Tehnologije

- Python, PyTorch  
- segmentation-models-pytorch, efficientnet-pytorch  
- Albumentations, PIL, NumPy, Matplotlib  

---

## Pokretanje

1. Kloniraj repozitorij i kreiraj virtualno okruženje:
bash
git clone https://github.com/AntonelaGalicc/Racunalni-vid.git
cd Racunalni-vid
python -m venv .venv
source .venv/bin/activate

2. Instalacija:
pip install -r requirements.txt

--- 
## Funkcionalnosti:
1. Trening i evaluacija modela za segmentaciju (UNet, FPN, DeepLabV3…)
2. Izračun metrika: IoU i Dice score
3. Vizualizacija: slike, ground truth maske, predikcije, overlay i heatmap

