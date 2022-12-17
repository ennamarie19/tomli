# Build Stage
FROM fuzzers/atheris:2.0.7-python3.9

# Install dependencies

ADD . /tomli
WORKDIR /tomli
RUN python3 -m pip install . tomli_w

CMD ["python3", "/tomli/fuzzer/fuzz.py"]
