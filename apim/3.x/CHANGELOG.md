# Changelog

This file documents all notable changes to [ingress-nginx](https://github.com/gravitee-io/helm-charts/tree/master/apim/3.x) Helm Chart. The release numbering uses [semantic versioning](http://semver.org).

### 3.1.4

- [X] [#94](https://github.com/gravitee-io/helm-charts/pull/94) Do not apply special treatment for nightly tag
- Update gravitee.io APIM v3.7.0

### 3.1.3

- [X] Disable HTTP proxy by default

### 3.1.2

- [X] Addition of configuration values for the kubernetes controller plugins
- [X] Add configuration for Elasticsearch ILM
- [X] Map handlers for API Gateway to override X-Transaction and X-Request
- [X] Portal extraInitContainers mapped to ui

### 3.1.1

- [X] Add support for extended reporters configurations
- [X] Allow to configure trustAll for identity providers

### 3.1.0

- [X] Manage default plugins
- Update gravitee.io APIM v3.6.0

### 3.0.21

- [X] Add authSource field to ratelimit section
- Update gravitee.io APIM v3.5.3

### 3.0.20

- [X] Allows to deploy nightly version of APIM
- [X] Add mongo authSource field to configmaps when not using Mongo URI

### 3.0.19

- [X] Externalize securityContext from deployments

### 3.0.18

- [X] Enable technical api for api and gateway by default
- [X] Add sane default value for technical api password
- [X] Add gateway technical api spec to values.yaml
- [X] Add technical ingress to gateway, like what was done for api-component
- [X] Add technical api spec to gateway service
- [X] Parametrize technical api portion of gateway configmap
- [X] Add technical api enable flag and auth type options to api-configmap
- [X] Update ui-deployment.yaml
- [X] Minor ingress improvements 

### 3.0.17

- Update gravitee.io APIM v3.5.2

### 3.0.16

- Update gravitee.io APIM v3.5.0

### 3.0.15

- [X] Fix mongo env var overloading using helm
- [X] Add default company name to values.yaml
- [X] Add company name to template
- [X] Update Helm dependencies repository
- [X] Allow to configure the fullname of services, deployments, ...
- [X] Add condition for replica setting
- [X] Simplify configuration of jdbc driver and other plugins

### 3.0.14

- [X] Add custom management console URL handling resolve

- Update gravitee.io APIM v3.4.0

### 3.0.13

- [X] Allow the configuration of an OIDC provider
- [X] Fix helm requirements
- [X] Add support for sidecar containers
- [X] Add APIM redis example + remove values examples

### 3.0.12

- [X] Add support for HTTP bridge deployment
- [X] Fix issue with smtp templating values

- Update gravitee.io APIM v3.3.3