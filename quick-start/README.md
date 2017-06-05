# Pre-requisites

Enable shared mounts: 

```
sudo mount --make-shared /
```

More info at: [https://docs.portworx.com/knowledgebase/shared-mount-propogation.html] (https://docs.portworx.com/knowledgebase/shared-mount-propogation.html)


# Running PX-Dev with Docker Compose custom image

You can start `PX-Dev` with [docker-compose](https://docs.docker.com/compose/install/) as follows:

```
# git clone https://github.com/chavezom/px-dev.git
# cd px-dev/quick-start
# docker-compose up -d
```

You now have a scale-out storage cluster for containers. Continue with more examples and [Quick Start Guides](https://github.com/portworx/px-dev/blob/master/README.md#install-and-quick-start-guides). 

This release is an beta and we want to develop this solution with the community. [Contact us](https://github.com/portworx/px-dev#contact-us) to share your feedback, work with us, and to request features. Stay tuned for updates on PX-Dev and our PX-Enterprise release. 
