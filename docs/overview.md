# Overview:

This repository will contain both ansible and terraform scripts which I am developing as I learn the intricasies of both IAC frameworks.

## Goal:

The goal is to be able to create a set of compute instances, some block storage buckets and a load balancer connected to the compute instances.

Each compute instance will have certain packages installed on it and some management scripts and configuration files will be added to each instance.

The object storage buckets will be created, and a sample file uploaded to the buckets.

The load balancer will be created with a backend routing to the compute instances in a round-robin fashion.
