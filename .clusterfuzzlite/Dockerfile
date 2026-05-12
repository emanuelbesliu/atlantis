FROM gcr.io/oss-fuzz-base/base-builder-go@sha256:9384182542a9ad08cb7dd1fbcbd9b30375ab1bc74fe7601249a0f1d95e04d706
COPY . $SRC/atlantis
COPY .clusterfuzzlite/build.sh $SRC/build.sh
WORKDIR $SRC/atlantis
