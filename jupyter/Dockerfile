FROM  jupyter/datascience-notebook

ENV JUPYTER_ENABLE_LAB=yes
ENV NB_PREFIX /
ENV GRANT_SUDO=yes
ENV SHELL=bash
ENV RESTARTABLE=yes
RUN jupyter labextension install @axlair/jupyterlab_vim

EXPOSE 8888

CMD jupyter lab  \
	--notebook-dir=/home/jovyan \
	--no-browser \
	--ip=0.0.0.0  \
	--allow-root  \
	--port=8888  \
	--NotebookApp.token='' \
	--NotebookApp.base_url=NB_PREFIX \
	--NotebookApp.password='' \
	--NotebookApp.allow_origin='*'