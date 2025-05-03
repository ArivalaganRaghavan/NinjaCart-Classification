# NinjaCart Classification

# Multi-Class Vegetable Classification  
### Identifying Onion, Potato, Tomato & Market Scenes  

## Overview  
This project builds a multi-class image classifier to recognize vegetables (onion, potato, tomato) and differentiate them from noise (Indian market scenes). Using exploratory data analysis (EDA), CNNs, and transfer learning, we improved model performance significantly.  

## Approach  
- **Data Preparation**: Scraped and analyzed dataset for class imbalance.  
- **Baseline CNN Model**: Achieved **80.91% accuracy** on test data.  
- **Transfer Learning**: MobileNetV2 and ResNet50 raised accuracy to **93.45%**.  
- **Fine-Tuning**: Improved ResNet50 model with selective layer unfreezing for better generalization.  

## Results  
- **Baseline Model**: 80.91% accuracy  
- **MobileNetV2 Transfer Model**: 93.45% accuracy  
- **ResNet50 Transfer Model**: 92.31% accuracy  
- **Fine-Tuned ResNet50**: 93.45% accuracy  

## Key Takeaways  
- Transfer learning significantly boosts model accuracy.  
- Fine-tuning ResNet layers leads to better generalization.  
- MobileNetV2 provides a balance between accuracy and efficiency.  

## How to Run  
1. Clone the repo:  
 
2. Install dependencies:

3. Train and test the model using the provided Jupyter notebooks.  

## Future Improvements  
- Expand dataset for more diverse market scenes.  
- Experiment with additional architectures like EfficientNet.  

## Author  
Arivalagan Raghavan  
