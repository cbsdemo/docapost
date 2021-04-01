# docapost

docker run \
  --rm \
  --volume $PWD:/data \
  bentonam/fakeit \
  fakeit console \
  --count 10 \
  /data/docapost2.yaml
