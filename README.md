# Splunk Useful Links
Collection of useful tools/apps either written by me or others


## Administration Tools
[Splunk Install Script](https://github.com/johnciavarella/splunk_install) - Bash install splunk script for linux

## Splunk Searches and Dashboards
[Useful list of Splunk Searches](https://github.com/johnciavarella/splunk-searches) - A collection of useful Splunk searches. Includes REST and internal introspection searches

[Data Dictionary](https://github.com/johnciavarella/splunk-data-dictionary) - Data Dictionary, data explorer and useful "Splunk on Splunk" tool for admins and beginners alike!

## Splunk TAs (Unlisted on Splunkbase)
[Silverpeak SDWan](https://github.com/johnciavarella/TA_Silverpeak_SDWAN) - TA for Silver Peak - [SDWan Technology](https://www.silver-peak.com/)

## Use same Splunk Secret between server
[Blog Post](https://hurricanelabs.com/splunk-tutorials/update-splunk-secret-without-breaking-your-production-environment/) - The ability to use the same Secret between all of your Splunk servers so you can rsync/copy encrypted passwords between servers. Useful if doing DR servers with copy of conf files.

# External

## Automation Tools 

[Ansible](https://github.com/splunk/splunk-ansible) - The official Splunk repository containing Ansible playbooks for configuring and managing Splunk Enterprise and Universal Forwarder deployments. This repository contains plays that target all Splunk Enterprise roles and deployment topologies that work on any Linux-based platform.

[Chef](https://github.com/sous-chefs/chef-splunk) - This cookbook manages a Splunk Universal Forwarder (client) or a Splunk Enterprise (server) installation, including a Splunk clustered environment.

[Terraform](https://github.com/splunk/terraform-provider-splunk) - Terraform Provider for Splunk

[Puppet](https://github.com/voxpupuli/puppet-splunk) - This module provides a method to deploy Splunk Enterprise or Splunk Universal Forwarder with common configurations and ensure the services maintain a running state. It provides types/providers to interact with the various Splunk/Forwarder configuration files.

## Splunk Connect

[Kubernetes](https://github.com/splunk/splunk-connect-for-kubernetes) - Splunk Connect for Kubernetes provides a way to import and search your Kubernetes logging, object, and metrics data in your Splunk platform deployment. Splunk Connect for Kubernetes supports importing and searching your container logs on the following technologies:

[Kafka](https://github.com/splunk/kafka-connect-splunk) - Splunk Connect for Kafka is a Kafka Connect Sink for Splunk.

[Syslog](https://github.com/splunk/splunk-connect-for-syslog) - Splunk Connect for Syslog is an open source packaged solution for getting data into Splunk using syslog-ng (OSE) and the Splunk HTTP event Collector.

## Administration/Server
[Event Gen](https://github.com/splunk/eventgen) - Splunk Event Generator is a utility that helps users easily build real-time event generators.

[Splunk on Docker](https://github.com/splunk/docker-splunk) -  The official Splunk repository of Dockerfiles for building Splunk Enterprise and Splunk Universal Forwarder images for containerized deployments.

[VIM Syntax Highlighting](https://github.com/yorokobi/vim-splunk) - Syntax highlighting for Splunk's .conf files


## SDKs

[SDK Java](https://github.com/splunk/splunk-sdk-java) - The Splunk Software Development Kit (SDK) for Java contains library code and examples designed to enable developers to build applications using Splunk.

[SDK Javascript](https://github.com/splunk/splunk-sdk-javascript) - The Splunk Enterprise Software Development Kit (SDK) for JavaScript contains library code and examples designed to enable developers to build applications using the Splunk platform and JavaScript. This SDK supports server-side and client-side JavaScript.
