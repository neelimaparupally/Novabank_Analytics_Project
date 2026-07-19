## Project Deliverables

- [View the executive memo](NovaBank_Executive_Memo.pdf)
- [Download the presentation](NovaBank_Analytics_Methods_Framework_Presentation_NeelimaParupally.pdf)
- [Open the analysis notebook](novabank_analysis_submission_ready.ipynb)

## Author

Neelima Parupally  
MSBA Candidate, Quantic School of Business and Technology  
July 2026

# NovaBank Predictive Outreach Decision Support

Prepared by **Neelima Parupally** for the Quantic MSBA Analytics Methods and Frameworks project.

## Project summary

This project builds a practical decision-support framework for NovaBank customer outreach prioritization. The public dataset measures whether a bank client responded positively to a term-deposit campaign. For the NovaBank case, that response is used as a proxy for likely retention/outreach engagement. The final recommendation is to pilot a model-driven ranked outreach strategy before any full rollout.

## Important assumption

The dataset does **not** contain actual churn outcomes. Any retention language is a business framing assumption. Financial values such as false-positive cost and false-negative cost are illustrative scenario inputs and should be validated through a pilot.

## Repository contents

- `novabank_analysis_submission_ready.ipynb` - reproducible notebook
- `bank-additional-full.csv` - dataset used by the notebook
- `NovaBank_Submission_Ready_Deck.pptx` - 10-slide appendix deck
- `NovaBank_Submission_Ready_Executive_Memo.pdf` - one-page executive memo
- `figures/` - charts used in the analysis and deck
- `requirements.txt` - Python packages

## How to run

1. Download or clone this repository.
2. Open `novabank_analysis_submission_ready.ipynb` in Jupyter, VS Code, or Google Colab.
3. Make sure `bank-additional-full.csv` is in the same folder as the notebook.
4. Install dependencies:

```bash
pip install -r requirements.txt
```

5. Run the notebook from top to bottom.

## Main recommendation

Use the gradient boosting model to rank customers and pilot outreach to the highest-scored 20%. Validate business value through a 90-day experiment with a randomized control group before scaling.

## AI usage disclosure

AI tools were used to help structure the narrative, review code for gaps, improve executive wording, and identify unsupported claims. Final assumptions, recommendations, and submission choices were reviewed and owned by the analyst.

## Dataset citation

Moro, S., Cortez, P., & Rita, P. (2014). *A data-driven approach to predict the success of bank telemarketing*. Decision Support Systems.
