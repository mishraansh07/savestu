# Receipt Information Extractor

This project uses a LayoutLM model to automatically extract key information (Company, Date, Address, Total) from scanned receipt images.

## Setup

1.  Clone the repository.
2.  Create a virtual environment: `python -m venv venv`
3.  Activate it: `.\venv\Scripts\Activate.ps1`
4.  Install dependencies: `pip install -r requirements.txt`

## Training

To train the model, run the main script:
`python run_training.py`
