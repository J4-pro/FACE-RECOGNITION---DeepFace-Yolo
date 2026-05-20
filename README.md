# 🧠 Face Recognition TDR

Aquest projecte consisteix en el desenvolupament d’un sistema de reconeixement facial en temps real utilitzant intel·ligència artificial. El sistema és capaç de detectar i identificar persones a partir d’una càmera en directe, integrant diverses tecnologies de visió artificial i deep learning.

---

## 🚀 Funcionalitats

- ✅ Detecció de cares en temps real amb YOLOv8
- ✅ Reconeixement facial amb DeepFace (model ArcFace)
- ✅ Sistema de comparació mitjançant embeddings
- ✅ Càlcul de similitud amb distància cosinus
- ✅ Tracking de cares entre fotogrames
- ✅ Sistema de millora de resultats amb historial
- ✅ Classificació en: identificat / dubtós / desconegut
- ✅ Interfície web en temps real amb Flask

---

## 🧠 Tecnologies utilitzades

- Python
- OpenCV
- YOLOv8 (Ultralytics)
- DeepFace
- ArcFace
- Flask
- NumPy
- Multiprocessing

---

## ⚙️ Funcionament del sistema

El sistema segueix el següent pipeline:

1. 📷 Captura de vídeo en temps real
2. 🔍 Detecció de cares amb YOLOv8
3. 🧠 Extracció d’embeddings amb DeepFace (ArcFace)
4. 📊 Comparació amb la base de dades
5. 📐 Càlcul de distància cosinus
6. ✅ Decisió final (identitat)
7. 🔁 Filtratge mitjançant historial
8. 🌐 Visualització a la interfície web

---

## 🧪 Resultats

- Precisió aproximada: ~80%
- Execució en temps real
- Compatible amb ordinadors convencionals

---

## ▶️ Com executar el projecte

### 1. Clonar el repositori
