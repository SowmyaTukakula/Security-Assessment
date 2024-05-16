The project will be conducted in layers to be able
to correctly perform a security assessment in the
iSpy software.

A. Information gathering
Firstly, we would gather information about the
software such as the source code, documentation
and the software’s website itself, and these are all
readily available on GitHub. This would help
understand the system architecture, features and
attack surface.

B. Identification of Threats and Vulnerabilities
Next, we identify the threats and vulnerabilities
present in the software. Using both static and
dynamic vulnerability analysis techniques such as
- Vulnerability assessments (or scanning
using scanners like Tenable Nessus or
OpenVAS)
- Source code Analysis or code review, which
would help find insecure code such as
unvalidated user input.
- Penetration Testing would allow testing for
vulnerabilities such as buffer overflows,
cross site scripting, cross site request
forgery and SQL injection.
- Fuzz testing: would use inputs such as login
credentials and camera URLs to find
potential crashes that may point us to
vulnerabilities present
- Runtime Analysis would allow for potential
vulnerabilities to be discovered by
highlighting unusual/abnormal behaviors in
the system during process execution.

C. Analyzing Potential Risks/ Threat Analysis
Then we identify the potential impacts of the
vulnerabilities using the DREAD model. We would
also use the STRIDE model to identify and rate
potential attacks.

 GOAL
The goal of this project is to perform a security
assessment on an open source software (our team
picked iSpy). By performing the assessment on the
software, we can all identify and comprehend
potential security vulnerabilities in iSpy and gain a
deeper understanding into the stages of a security
assessment, how it is performed and the uses.

 CONCLUSION
In conclusion, this project proposal outlines our
goal to conduct a security assessment of iSpy by
analyzing the source code and documentation to
identify possible threats and vulnerabilities.
1
