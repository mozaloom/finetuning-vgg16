# finetuning-vgg16

Fine-tune a pre-trained VGG16 model for dog vs. cat classification.

## Files

- `dog-vs-cat-classification-vgg16.ipynb` – end-to-end notebook (data loading, model setup, training, evaluation).
- `.gitignore` – ignores environment and checkpoint files.
- `LICENSE` – MIT License.

## Quick Start

```bash
git clone https://github.com/mozaloom/finetuning-vgg16.git
cd finetuning-vgg16
python3 -m venv venv && source venv/bin/activate
pip install tensorflow matplotlib numpy pandas
jupyter notebook
```
