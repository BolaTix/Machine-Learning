# BolaTix Machine Learning
Developing a recommendation system for BolaTix that delivers personalized match suggestions to users. This system utilizes a content-based filtering model based on users' purchase history. To address the cold-start problem, the recommendation system incorporates users' favorite teams selected during the registration process, ensuring relevant and engaging match recommendations from the start.

## Project Structure
- **`Dataset/Dataset Liga 1 2024-2025.csv`**: Indonesian Liga 1 dataset that we created.
- **`Model/Coldstar.h5`**: System recommendation model based on favorite team.
- **`Model/RekomendasiHistoryr.h5`**: System recommendation model based on User History.
- **`Cold_Start.ipnyb`**
- **`RekomendasiHistory.ipnyb`**
  
## ML Architecture
![image](https://github.com/BolaTix/Machine-Learning/blob/main/Images/ML%20Architecture.png)

## Model Performance
| Metric                       | Value         |
|------------------------------|---------------|
| **Cross-Validation Results** |               |
| Average Validation Loss      | 0.1226        |
| Standard Deviation           | 0.0055        |
| **Model Evaluation**         |               |
| Mean Squared Error (MSE)     | 4.5073        |
| Mean Absolute Error (MAE)    | 1.6780        |
| **Second Evaluation**        |               |
| Mean Squared Error (MSE)     | 4.3175        |
| Mean Absolute Error (MAE)    | 1.6484        |

The model was trained for 100 epochs with the following validation loss trends:
| Epoch | Training Loss | Validation Loss |
|-------|---------------|-----------------|
| 1     | 3.2054        | 0.8781          |
| 10    | 0.1166        | 0.1172          |
| 50    | 0.0830        | 0.0900          |
| 100   | 0.0794        | 0.0884          |

![image](https://github.com/BolaTix/Machine-Learning/blob/main/Images/hasil%20training.png)
