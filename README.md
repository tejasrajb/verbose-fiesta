# verbose-fiesta

SIT744 Assignment 4: adapting `distilgpt2` to Australian parliamentary reports (full fine-tuning vs LoRA).

| File | What it is |
|---|---|
| `SIT744_assignment4_solution.ipynb` | Executed notebook, built from the student template (rename to `[YourID]_SIT744_assignment4_solution.ipynb`) |
| `SIT744_assignment4_output.pdf` | PDF export of the notebook (rename to `[YourID]_SIT744_assignment4_output.pdf`) |
| `undrip_train.txt`, `undrip_val.txt`, `economic_test.txt` | The three text files created in Task 1 |
| `source_documents/` | The two downloaded APH committee reports (UNDRIP .docx, Economic self-determination .pdf) |

Run the notebook from this folder (`jupyter nbconvert --to notebook --execute --inplace SIT744_assignment4_solution.ipynb`).
It takes about 10 minutes on a 4-core CPU. Requirements: `transformers datasets accelerate peft python-docx pypdf matplotlib pandas torch`.
