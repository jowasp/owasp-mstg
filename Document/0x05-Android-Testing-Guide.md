# Testing Application Security on Android

## Preparing the test environment
### Configuring  Rooted Devices
### Hardware
### Tools

## Android Application Mapping
### Retrieve package information with Drozer
### Navigate Application
### Create Inventory, Input fields UX
### Threat Modeling Analysis for Android apps
#### Identify the Attack Surface with Drozer
#### Launching Activities

## Code Review
#### Verifying Secure Implementation of WebViews
#### Verifying Secure implementation of Data Storage
#### Verifying Proper permissions in Android Manifest
#### Verify proper configuration of Security Configuration File
##### Pinning Certificate
##### CA and Set of Trusted CA's
##### Clear Text Traffic
#### Correct use of cryptology
#### Android Lint Static Analyzer

## Client Attacks
### Reverse Engineering

#### Static Analysis of APK with MobSF and Bytecodeviewer
##### Testing implementation of Obfuscation

#### Code Manipulation with Frida & Xposed
##### Testing implementation of Secure communications
##### Testing implementation of Certificate Pinning
##### Testing Device Rooted detetection
##### Testing Secure Cryptography
##### Testing Weak Authentication
##### Testing Weak Authorization

### Testing Data Leakage
#### Testing Internal Storage access 
#### Testing External Storage access
#### Testing Content Providers access with Drozer
##### Testing Database-backed Content Providers (Data Leakage)
##### Testing Database-backed Content Providers (SQL Injection) 
##### Testing File System-backed Content Providers
