# docapost

docker run \
  --rm \
  --volume $PWD/models:/data \
  bentonam/fakeit \
  fakeit console \
  --count 10 \
  /data/docapost2.yaml
