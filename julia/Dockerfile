FROM julia:1.6.1-buster
ENV JULIA_PROJECT=/opt/ml
WORKDIR /opt/ml
COPY *.toml  ./
RUN  julia -e 'import Pkg; Pkg.instantiate(); Pkg.precompile()'
ENTRYPOINT [ "julia"]