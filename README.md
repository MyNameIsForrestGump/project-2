# Clasificarea bolilor cartofului folosind Transfer Learning (ResNet18)

## Dataset

Am utilizat imagini din dataset-ul public **PlantVillage**, disponibil pe [Kaggle](https://www.kaggle.com/datasets/emmarex/plantdisease).

Au fost selectate trei clase, cu un total de **2.152 de imagini**, împărțite în 80% pentru antrenare și 20% pentru validare, aproximativ pentru fiecare clasă.

| Clasă | Antrenare | Validare |
|---|---:|---:|
| Potato Early Blight | 800 | 200 |
| Potato Late Blight | 800 | 200 |
| Potato Healthy | 121 | 31 |
| **Total** | **1.721** | **431** |

Dataset-ul este dezechilibrat, deoarece clasa Healthy conține semnificativ mai puține imagini.


## Rezultate

| Epocă | Loss raportat | Accuracy pe validare |
|---|---:|---:|
| 1 | 54.775 | 88,6% |
| 2 | 30.551 | 85,8% |
| 3 | 26.388 | **89,8%** |

### Rezultatul final

**Validation Accuracy: 89,8%**

Am avut trei epoci de antrenare.

