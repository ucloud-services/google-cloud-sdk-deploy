FROM google/cloud-sdk:408.0.1-alpine

RUN apt-get update && \
    apt-get install -y -q gettext google-cloud-sdk-gke-gcloud-auth-plugin && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*
