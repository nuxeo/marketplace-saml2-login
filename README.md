## Nuxeo SAML 2.0 Authentication

## About

This project allows building the Marketplace package for the
[SAML 2.0 Authentication](https://github.com/nuxeo/nuxeo-platform-login/tree/master/nuxeo-platform-login-saml2) addon.

For further information please read the [documentation](https://doc.nuxeo.com/x/QIVkAQ).

## Building

To build and run the tests, simply start the Maven build:

    mvn clean install

To run functional tests:

    mvn clean install -Pftest

## Installing

To install the package:

 1. Take a fresh Nuxeo CAP (>= 7.3).

 2. Install the saml2-authentication package:
      - From the AdminCenter (Upload + install)
      - From the command line using `nuxeoctl mp-install package.zip`
