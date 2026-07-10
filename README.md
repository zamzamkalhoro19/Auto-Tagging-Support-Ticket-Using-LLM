# Auto-Tagging-Support-Ticket-Using-LLM
## Objective
Automatically tag free-text customer support tickets into categories using 
prompt engineering and LLM-based text classification. The system predicts 
the top 3 most probable tags per ticket, ranked by confidence.

## Approach
- Dataset loading & preprocessing of support ticket text
- Zero-shot classification prompt design
- Few-shot classification prompt design (in-context examples)
- Comparison: Zero-shot vs Few-shot vs Fine-tuned performance
- Evaluation using Top-1 and Top-3 accuracy, classification report, 
  confusion matrix
- Final output: top 3 predicted tags per ticket

## Results
| Approach     | Top-1 Accuracy | Top-3 Accuracy |
|--------------|---------------|-----------------|
| Zero-Shot    | 0.68          | 0.92            |
| Few-Shot     | 0.88          | 0.96            |
| Fine-Tuned   | 0.88          | 0.96            |

## Files
- `Task5_Auto_Tagging_Support_Tickets.ipynb` — full notebook with code, 
  evaluation, and visualizations
- `support_ticket_top3_tags.csv` — final output with top-3 tags per ticket

## Skills Demonstrated
Prompt engineering, LLM-based text classification, zero-shot & few-shot 
learning, multi-class prediction and ranking
