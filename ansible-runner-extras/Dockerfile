FROM ansible/ansible-runner:latest

ADD run.sh /tmp/run.sh

RUN chmod +x /tmp/run.sh \
  && /tmp/run.sh

RUN rm /tmp/run.sh