FROM jupyter/datascience-notebook

RUN pip install --no-cache-dir imbalanced-learn xgboost lightgbm jupyter_http_over_ws && \
	jupyter serverextension enable --py jupyter_http_over_ws