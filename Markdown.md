# Ethical Hacking Technical Report

**Client:** [Fujitsu Global]  
**Date:** [May 11, 2024]  
**Prepared by:** [Ralph H. Lorzano] and [Fermin Jr. III H. Turiano]

## Executive Summary
This report presents the technical findings of the ethical hacking assessment conducted for Fujitsu Global. Fujitsu, a global IT services provider, underwent an ethical hacking assessment to identify vulnerabilities, assess risk, and recommend remediation measures. 

The findings of the security evaluation done on Fujitsu Global are presented in this report. Penetration testing and vulnerability assessment were two of the testing approaches used to find possible security vulnerabilities.

This evaluation found 10 high-risk and significant vulnerabilities. Malicious actors could take advantage of these vulnerabilities to access the system without authorization, compromise confidential information, or interfere with essential functions.

Each vulnerability that has been found is thoroughly described in this report, along with information on its possible effect and suggested remediation actions.


## Vulnerability Summary

### 1. Network Vulnerabilities
- The presence of obsolete software versions on a number of systems exposed them to known vulnerabilities.
- There were found to be weak password rules, which may have led to unwanted access.

### 2. Web Application Security
- Common security vulnerabilities, such as SQL injection and cross-site scripting (XSS), were present in the company's online applications.
- There was a potential for data manipulation attacks due to poor input validation methods.


### 3. Wireless Network Security
- The wireless network has weak encryption methods that allow for easy eavesdropping.
- Unauthorized devices were able to establish connections to crucial network segments due to improper segmentation.


### 4. Endpoint Security
- Malware infections were more likely on some client devices as they did not have the most recent antivirus software.
- Unsuitable control over removable media, such as USB devices, created a danger of data leakage.


### 5. Social Engineering Vulnerabilities:
- Employees were susceptible to phishing attacks due to insufficient awareness training.
- Physical security controls were inconsistent across office locations.

### 6. Insufficient Logging and Monitoring:
- Systems from Fujitsu lacked extensive logging and monitoring features.
- It would be difficult to identify and address security problems without accurate logs.


### 7. Third-Party Vendor Risks
- The business depended on a number of outside suppliers for essential services.
- There was inconsistent performance of vendor security evaluations.


### 8. Default Credentials
- Several network apps and devices continued to utilize the default login information.
- It's imperative to modify default passwords in order to stop unwanted access.


### 9. Inadequate Incident Response Plan
- There was not a clear incident response plan at Fujitsu.
- To reduce the effect of security events, a strong plan is essential.


### 10. Unpatched Software
- Some software components were out of date, which made them open to hacking.
- Patch management on a regular basis is crucial.

## Recommendations

### 1. Patch Management
- Update software often to fix known vulnerabilities.
- Use tools for automatic patch management.


### 2. Password Policies
- Implement robust password policies throughout the whole company.
- When it is feasible, use multi-factor authentication (MFA).


### 3. Web Application Security
- Perform comprehensive security testing for online applications, including code reviews and penetration tests.
- To stop frequent assaults, use output encoding and input validation.


### 4. Wireless Network Hardening
- Update wireless network encryption algorithms (such as WPA3).
- To separate important systems, segment wireless networks.

### 5. Employee Training
- Employees should get frequent security awareness training.
- Practice phishing simulations to increase resilience.


### 6. Enhance Logging and Monitoring:
- Put real-time monitoring and centralized logging into practice.
- Examine logs often for indications of questionable behavior.


### 7. Vendor Security Assessments
- Perform regular security assessments of third-party vendors.
- Ensure vendors meet security standards.


### 8. Change Default Credentials
- Use strong, one-of-a-kind passwords to replace the default ones.
- Put in place a policy for password rotation.


### 9. Develop an Incident Response Plan
- Make an extensive plan for responding to incidents.
- Establish roles, duties, and channels of communication.


### 10. Prioritize Software Updates
- Create a procedure for installing software updates on schedule.
- Keep an eye out for important fixes in vulnerability databases.

## Conclusion
Fujitsu should prioritize addressing the identified vulnerabilities promptly to enhance its overall security posture. By implementing the recommended measures, the company can better protect its data, systems, and reputation.

**Signature:** [Lorzano, Ralph H.]  [Turiano, Fermin Jr. III H.]
