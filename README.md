# Setup Environment - ANACONDA

- conda create --name main-ds python=3.9
- conda activate main-ds
- pip install -r requirements.txt
- conda create -n streamlit_env python=3.9
- conda activate streamlit_env
- conda install pandas seaborn matplotlib numpy streamlit


# Setup Environment - Shell/Terminal

- mkdir proyek_analisis_data
- cd proyek_analisis_data
- pipenv install
- pipenv shell
- pip install -r requirements.txt

# Run Streamlit App

streamlit run dashboard.py
