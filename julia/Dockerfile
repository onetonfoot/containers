FROM julia:1.6.1
COPY *.toml ./
RUN julia  --project=./  -e "using Pkg; Pkg.instantiate(); Pkg.precompile()"
ENTRYPOINT [ "julia", "--project=./"]