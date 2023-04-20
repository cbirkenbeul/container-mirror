# Container Images Mirror

Stop-gap container registry mirror of upstream applications that only use Docker Hub

## Purpose

This is to get around Docker Hub rate-limiting (100 pulls / 6 hours, or authenticated 200 pulls / 6 hours). It is considered a stop-gap until the maintainers of the applications below support a different Container Registry.

## Docker OSS Program

Certain containers may not be rate limited if they are in Docker Hub's OSS Program. Below is a list of applications I have discovered to be part of this program.

- bitnami/*
- intel/intel-deviceplugin-operator
- intel/intel-gpu-plugin
- nodered/node-red
- rook/ceph