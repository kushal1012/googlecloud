# googlecloud

commands GCR
1.docker built -t gcr.io/{PROJECT-ID}/test-gcr
2.gcloud auth print-access-token | docker login -u oauth2accesstoken \
    --password-stdin https:gcr.io
3.docker push gcr.io/{PROJECT-ID}/test-gcr:v01
4.gcloud auth activate-service-account {Serviceaccountname} --key-file=key-file.json
