---
permalink: /NIST-800-53/SI-2/
title: SI-2 - Flaw Remediation
parent: NIST-800-53 Documentation
---

## Nessus
a. - Flaw identification is accomplished via Nessus, AlienVault USM, OWASP Zap, and Code Climate static code analysis.  Nessus is a vulnerability, configuration, and compliance scanner.
 
 
### References

* [Nessus Website](http://www.tenable.com/products/nessus-vulnerability-scanner)

--------

## OWASP Zap
a. OWASP Zap (Web Application scanner and penetration test tool) for monthly scanning of all web applications that reside within Cloud Foundry. Upon implementation of the application, authenticated (Web Application) scans will be run on Test instances of the code every major release and minor releases when the release contains a change with a potential security impact.  OWASP Zap reports are reviewed after each scan and appropriate actions taken on discovery of vulnerabilities.
 
 
### References

* [OWASP Zap Site](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project)

--------

## BOSH Stemcells
Cloud Foundry manages software vulnerability using releases and BOSH stemcells. New Cloud Foundry releases located at https:/github.com/cloudfoundry/cf-release, are created with updates to address code issues, while new stemcells are created with patches for the latest security fixes to address any underlying operating system issues.
### References

* [Bosh StemCells](https://bosh.io/stemcells)

* [Bosh updates](https://github.com/cloudfoundry/bosh/blob/master/bosh-stemcell/OS_IMAGES.md)

* [New BOSH stemcells](http://boshartifacts.cloudfoundry.org/file_collections?type=stemcells)

* [Bosh Ubuntu trusty specs](https://github.com/cloudfoundry/bosh/blob/master/bosh-stemcell/spec/stemcells/ubuntu_trusty_spec.rb)

--------