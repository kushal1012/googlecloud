# googlecloud

commands GCR
docker built -t gcr.io/{PROJECT-ID}/test-gcr

docker push gcr.io/{PROJECT-ID}/test-gcr:v01
gcloud auth print-access-token | docker login -u oauth2accesstoken \
    --password-stdin https:gcr.io

gcloud auth activate-service-account {Serviceaccountname} --key-file=key-file.json
