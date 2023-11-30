# googlecloud

commands GCR
docker built -t gcr.io/{PROJECT-ID}/test-gcr

docker push gcr.io/{PROJECT-ID}/test-gcr:v01

gcloud auth activate-service-account {Serviceaccountname} --key-file=key-file.json
