# googlecloud

commands GCR
# docker built -t gcr.io/{PROJECT-ID}/test-gcr
# gcloud auth print-access-token | docker login -u oauth2accesstoken \
    --password-stdin https:gcr.io
# docker push gcr.io/{PROJECT-ID}/test-gcr:v01
# gcloud auth activate-service-account {Serviceaccountname} --key-file=key-file.json
