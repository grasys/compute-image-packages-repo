# github

https://github.com/GoogleCloudPlatform/compute-image-packages

# Setup

/etc/yum.repos.d/compute-image-packages.repo

```
curl -s -o /etc/yum.repos.d/compute-image-packages.repo http://grasys.github.io/compute-image-packages-repo/compute-image-packages.repo
```

# yum update

```
yum --enablerepo=google-compute-image-packages update
```

# createrepo

```
createrepo CentOS/GoogleCloudPlatform/
```
