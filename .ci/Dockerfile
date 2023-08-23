FROM google/cloud-sdk

RUN apt-get update && \
    apt-get install -y -q gettext google-cloud-cli

#RUN gke-gcloud-auth-plugin --version 
#RUN gke-gcloud-auth-plugin.exe --version

RUN gcloud components install gke-gcloud-auth-plugin
RUN gcloud components install kubectl
RUN gcloud components install beta
