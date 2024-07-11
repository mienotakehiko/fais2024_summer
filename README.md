# fais2024_summer

・This folder contains the needed material to reproduce our case-studies.　<br>
・Models can be validated using the latest Tamarin prover.

---
File Description

1.&emsp;notoracle_cpamodel_verification_symmetric-encryption.spthy <br>
2.&emsp;cpamodel_verification_symmetric-encryption.spthy <br>
3.&emsp;cpamodel_verification_symmetric-encryption.log <br>
4.&emsp;cpamodel_verification_symmetric-encryption_out.spthy <br>
5.&emsp;cpamodel_verification_symmetric-encryption_out.log <br>
6.&emsp;myoracle <br>

---
1.&emsp;notoracle_cpamodel_verification_symmetric-encryption.spthy <br>

 &emsp;&emsp;Verification code not using oracle <br>
 &emsp;&emsp;Verification results: verification does not stop <br>

2.&emsp;cpamodel_verification_symmetric-encryption.spthy <br>

 &emsp;&emsp;Verification code using oracle <br>
 &emsp;&emsp;Verification results: cpamodel_verification_symmetric-encryption.log <br>

3.&emsp;cpamodel_verification_symmetric-encryption.log <br>
 
 &emsp;&emsp;Result of running the above file: cpamodel_verification_symmetric-encryption.spthy <br>

4.&emsp;cpamodel_verification_symmetric-encryption_out.spthy <br>

 &emsp;&emsp;Verification code using oracle (however, the Sender side intentionally leaked the private key to the outside model) <br>
 &emsp;&emsp;Verification results: cpamodel_verification_symmetric-encryption.log <br>

5.&emsp;cpamodel_verification_symmetric-encryption_out.log <br>

&emsp;&emsp; Result of running the above file: cpamodel_verification_symmetric-encryption_out.spthy <br>

6.&emsp;myoracle <br>
 &emsp;&emsp;Oracle code described in python3 <br>

---
