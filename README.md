# Breast Cancer Detection

See what the model sees. Understand every prediction.. Upload a breast medical image, review the model's four-class prediction, and explore the regions that influenced its decision through Grad-CAM. This is an academic explainable-AI prototype for breast image analysis, with a FastAPI backend, React research interface, and the model is powered by CNNs, training, validation and testing sets and coded in the Python programming language. This ML project was built as the final team project for AI4ALL Ignite Summer Program.

## Problem Statement <!--- do not change this line -->

Breast cancer remains a leading cause of death among women, worsened by delayed diagnosis and limited healthcare access in low and middle income countries. Breast cancer survival exceeds 90% in high-income countries but drops to just 40% in South Africa (World Health Organization, 2025). Detected early, breast cancer has a 5-year survival rate of over 99%; once it spreads to distant organs, that rate falls to 31% (American Cancer Society, SEER Data, 2026). Breast cancer incidence among women under 50 is rising 1.4% per year, nearly double the rate in older women (American Cancer Society, 2024).

## Our Research Question
Can we accurately classify tissue as normal, benign, or a type of  malignant, while highlighting regions that influenced these decisions with a 90% certainty?

## Key Results <!--- do not change this line -->
The four-model ensemble was evaluated on a test set of **400 breast histopathology images** across four classes: Benign, Carcinoma In Situ, Invasive Carcinoma, and Normal.

### Overall Model Performance

| Metric | Score |
|---|---:|
| **Accuracy** | **86.75%** |
| Macro Precision | 87.13% |
| Macro Recall | 87.01% |
| Macro F1 | 86.66% |
| Weighted Precision | 87.38% |
| Weighted Recall | 86.75% |
| Weighted F1 | 86.62% |
| Test Samples | 400 |

### Per-Class Performance

| Class | Precision | Recall | F1 Score | Support |
|---|---:|---:|---:|---:|
| **Benign** | 93.62% | 76.52% | 84.21% | 115 |
| **Carcinoma In Situ** | 88.64% | 84.78% | 86.67% | 92 |
| **Invasive Carcinoma** | 83.87% | 88.64% | 86.19% | 88 |
| **Normal** | 82.40% | 98.10% | 89.57% | 105 |

![Confusion Matrix](Final%2018C%20Presentation.png)
### Key Findings

1. **Achieved 86.75% overall accuracy** across the 400-image test set using the four-model ensemble.
2. **Normal tissue achieved the highest recall at 98.10%**, meaning the ensemble correctly identified nearly all Normal samples in the test set.
3. **Benign tissue achieved the highest precision at 93.62%**, although its lower recall of 76.52% indicates that some Benign samples were classified as other classes.
4. **Normal tissue achieved the highest F1 score at 89.57%**, providing the strongest balance between precision and recall among the four classes.
5. **Macro precision, recall, and F1 remained near 87%**, indicating relatively consistent performance across the four tissue classes.

> **Note:** These results reflect evaluation on the repository's current 400-image test set and do not establish clinical effectiveness.
## Methodologies <!--- do not change this line -->

(UPDATE IN README.md)

*EXAMPLE:*
*To accomplish this, we utilized the OpenAI API to interact with ChatGPT, and we designed a custom Python script to generate diverse prompts and collect corresponding responses. The data was then processed and analyzed using pandas, enabling us to detect patterns and biases in the AI model's outputs.*
*Engineered a Python script to generate over 1,000 prompts and elicit their responses from ChatGPT, utilizing pandas to collect the data. When prompted for solutions to this specific relevant crisis, nearly 80% of ChatGPT's responses promoted a certain worldview.*


## Data Sources <!--- do not change this line -->

(UPDATE IN README.md)
Include any relevant data sources that were used in your project.

*EXAMPLE:*
*Kaggle Datasets: [Link to Kaggle Dataset](https://www.kaggle.com/datasets)*

## Technologies Used <!--- do not change this line -->

(UPDATE IN README.md)
List the technologies, libraries, and frameworks used in your project.

*EXAMPLE:*
- *Python*
- *pandas*
- *OpenAI API*


## Authors <!--- do not change this line -->

(UPDATE IN README.md)
List the names and contact information (e.g., email, GitHub profiles) of the authors or contributors.

*EXAMPLE:*
*This project was completed in collaboration with:*
- *John Doe ([john.doe@example.com](mailto:john.doe@example.com))*
- *Jane Smith ([jane.smith@example.com](mailto:jane.smith@example.com))*
