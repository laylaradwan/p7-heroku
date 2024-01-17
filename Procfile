web: uvicorn main:app --host=0.0.0.0 --port=${PORT:-5000}
worker: streamlit run dashboard.py --server.port=${PORT:-8501} --server.allow_origin='*'



