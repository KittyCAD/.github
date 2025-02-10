# Zoo Security Policy

Zoo welcomes feedback from security researchers and the general public to help improve our security.
 If you believe you have discovered a vulnerability, privacy issue, exposed data, or other security issues in any of our assets, we want to hear from you. 
 This policy outlines steps for reporting vulnerabilities to us, what we expect, and what you can expect from us.

## Systems in Scope

This policy applies to any digital assets owned, operated, or maintained by Zoo.

- Web services with domains matching *.zoo.dev or *.kittycad.io
- The Zoo Modeling App
- Open-source libraries and tools
- GitHub repositories and continuous integration

### Out of scope services include:
- Third-party services (such as cloud hosting, payment processing, or external authentication providers) are out of scope.
  Vulnerabilities discovered or suspected in out-of-scope systems should be reported to the appropriate vendor or applicable authority.
- Testing and development systems are out of scope.

## Our Commitments

When working with us, according to this policy, you can expect us to:

- Respond to your report promptly, and work with you to understand and validate your report;
- Strive to keep you informed about the progress of a vulnerability as it is processed;
- Work to remediate discovered vulnerabilities in a timely manner, within our operational constraints; and
- Extend Safe Harbor for your vulnerability research that is related to this policy.


## Our Expectations

In participating in our vulnerability disclosure program in good faith, we ask that you:

- Avoid violating the privacy of others, disrupting our systems, destroying data, and/or harming user experience;
- Make a good faith effort to avoid privacy violations, destruction of data, and interruption or degradation of live user production services;
- Limit security scanner requests to five per second;
- Provide us a reasonable amount of time (at least 90 days from the initial report) to resolve the issue before you disclose it publicly;
- Perform testing only on in-scope systems, and respect systems and activities which are out-of-scope;
- You should only interact with test accounts you own or with explicit permission from the account holder; and
- Do not engage in extortion.  

## Contact & Official Channel

Report general vulnerabilities at https://github.com/KittyCAD/cvd/security/advisories/new
If you know that a specific open-source service, library, program or tool is affected then create an GitHub advisory in the relevant repository at https://github.com/KittyCAD/[REPOSITORY]/security/advisories/new

Please make sure that you include the following information:
- Which service is affected?
- What is the bug?
- Which steps are required for reproducing the bug?
- How can the bug be exploited?
- What is the impact and risk for Zoo?

Reports will be answered within 72 hours. If you have not received an
answer within that time frame, feel free to contact us again.

We aim to patch critical vulnerabilities within 5 days.
However, fixing complex vulnerabilities may take up to 90 days.

The email security@zoo.dev must only be used for general security related inquires.
Do not use this email to disclose security vulnerabilities.

## Classification of Vulnerabilities

We will consider a vulnerability report most likely as relevant if it
reports one of the following problems:
- The vulnerability can be used to directly access non-public
  information that either reveals further security relevant problems or
  contains user data, credentials, or sensitive data in general.
- The vulnerability can be used to disrupt the orderly operation of a
  service (Denial of Service).
- The vulnerability can be used to manipulate data within the service.
- XSS, CSRF, RCE, authentication/authorization bypass, SQL injections,
  etc. are considered relevant.

We will consider a vulnerability report most likely as NOT relevant if
it reports one of the following problems:
- Missing security features, for example HTTP headers
- Publicly accessible version strings of used software.
- Security vulnerabilities that can only be used within the scope of the used account.
- The issue is not exploitable in a realistic scenario.

## Safe Harbor

When conducting vulnerability research, according to this policy, we consider this research conducted under this policy to be:

- Authorized concerning any applicable anti-hacking laws, and we will not initiate or support legal action against you for accidental, good-faith violations of this policy;
- Authorized concerning any relevant anti-circumvention laws, and we will not bring a claim against you for circumvention of technology controls;
- Exempt from restrictions in our Terms of Service (TOS) and/or Acceptable Usage Policy (AUP) that would interfere with conducting security research, and we waive those restrictions on a limited basis; and
- Lawful, helpful to the overall security of the Internet, and conducted in good faith.

You are expected, as always, to comply with all applicable laws. If legal action is initiated by a third party against you, and you have complied with this policy, we will take steps to make it known that your actions were conducted in compliance with this policy.

If at any time you have concerns or are uncertain whether your security research is consistent with this policy, please submit a report through one of our Official Channels before going any further.

> Note that the Safe Harbor applies only to legal claims under the control of the organization participating in this policy, and that the policy does not bind independent third parties.

## Bug Bounties

The amount of reward paid depends on the severity of the found
vulnerability. We usually do not pay rewards if vulnerabilities can be
found using automated scans with off-the-shelf software.

Only responsible disclosures are eligible for rewards.
