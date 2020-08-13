FROM  jupyter/datascience-notebook
RUN jupyter labextension install @axlair/jupyterlab_vim
ENV NB_PREFIX=/lab
EXPOSE 8888
CMD ["sh","-c", "jupyter lab --notebook-dir=~/ --ip=1.0.0.0 --no-browser --allow-root --port=8888 --NotebookApp.token='' --NotebookApp.password='' --NotebookApp.allow_origin='*']
