# Challenge
# Solution
## Steps
- [x] Provision Environment
- [x] Prepare and setup environment
- [] Deploy Local Polkadot Network
- [] Deploy Local Telemetry Server
- [] Aggregate Setup Scripts
- [] Automate Setup and Deployment in Ansible Script
- [] Run Final tests
- [] Tear Down Test environment
### Provision Environment
We will be working on AWS with a t2.medium instance as our test environment
### Setup Environment
We have prepared a bash script to prepare the instance with docker and a number of preliminary requirements used to run the network
```
bash code/prepare.sh
```