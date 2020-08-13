FROM  jupyter/datascience-notebook
RUN jupyter labextension install @axlair/jupyterlab_vim
EXPOSE 8888
CMD jupyter lab --notebook-dir=~/ --no-browser --ip=0.0.0.0 --allow-root --port=8888 --NotebookApp.token='' --NotebookApp.password='' --NotebookApp.allow_origin='*'
