# Solid CLI
A utility to facilitate command-line interaction with Solid servers.

## Installation
```
npm install -g @solid/cli
```

## Usage
```
IDP=https://drive.verborgh.org
USERNAME=ruben
PASSWORD=ruben
URL=https://drive.verborgh.org/inbox/

curl "$URL" -H 'Authorization: Bearer '`solid-bearer-token "$IDP" "$USERNAME" "$PASSWORD" "$URL"`
```
