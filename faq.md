# Frequently Asked Questions

## What is the cost of certification?
For [members](https://lfnetworking.org/about/members/) of LF Networking (LFN), there is no charge for certification. There is also no charge for non-profit organizations. For commercial organizations that wish to certify but don't want to become a LFN member, the fee is the same as [joining](https://lfnetworking.org/join/) the LFN.

## Is a participation form required per company or per product?
Per product. Each separate product (i.e., different product name) from your company requires a different [participation form](https://github.com/lfn-cnti/certification/blob/main/Certified_CNTi_Form.md). Submit a form to lfn-cnti@lfnetworking.org or another method made available by The Linux Foundation.

## How is CNTI Certification different from other conformance efforts?
While many network certifications test Kubernetes platform properties and Cloud Native Network Function (CNF) connectivity, LFN’s CNTI Certification Program gives insights into a CNF's installability, interoperability, and resilience. The certification also promotes workload self-healing as a highly desired, cloud native property.

## What score is needed to earn Certification?
The certification categorizes the tests into groups that are Normal, Essential and Bonus tests. In order to earn certification, the CNF must PASS 15 out of the 20 essential tests. You can review the list of tests [here](docs/CNTICertification-2.0-beta.md).

## What do "PASSED, FAILED, SKIPPED, N/A" mean while I'm running the Certification?
✔️ PASSED indicates the CNF passes the defined test based on the best practice. 
✖️ FAILED indicates it does not meet the requirements based on the best practice. 
⏩ SKIPPED indicates the test was skipped entirely, usually due to a service not installed that the test is checking against. An example SKIPPED would be our test that verifies if Prometheus is being used with the CNF or k8s cluster for monitoring and is not found to be in use. 
⏩ N/A indicates that the test does not apply, an example would be our SELinux_options test. If SELinux is not enabled, it's marked as N/A.

You'll need to pass (PASSED) 15 of the 20 marked Essential tests in order to become certified. See previous question for more details.

## I still have questions. Can you help?
Yes. Please email us at lfn-cnti@lfnetworking.org.
