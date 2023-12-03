# keycloak-gitops

## Objective

This repository contains multiple YAML files essential for setting up a Keycloak instance and its associated components like keycloakRealm, keycloakUser, etc. These configurations are intended to facilitate authentication for applications relying on Keycloak. The setup has been validated on an OCP v4.12.43 cluster equipped with the Red Hat SSO operator.

## Deployment

The various keycloak resources can be created by running the following command in the  directory where the README.md file is located:


```sh
oc apply -f resources/keycloak.yaml resources/keycloakClient.yaml resources/keycloakRealm.yaml resources/keycloakUser.yaml
```
