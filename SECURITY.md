# Zoo Security Policy

## 1. Services Covered by this Policy

This policy covers all services directly operated by Zoo.

Services include:
- Web services with domains matching *.zoo.dev or *.kittycad.io
- The Zoo Modeling App
- GitHub repositories and continuous integreation

## 2. Acceptable Use

We generally invite security researchers to search for vulnerabilities
in our services. We kindly ask to not put any actual user data or
production systems at risk. 

* Make a good faith effort to avoid privacy violations, destruction of data, 
  and interruption or degradation of live user production services. 
  Only interact with accounts you own or with the explicit permission of the account holder.
* Limit security scanner requests to five per second.
* Social engineering (e.g. phishing, vishing, smishing) is prohibited.

## 3. Classification of Vulnerabilities

We will consider a vulnerability report most likely as relevant if it
reports one of the following problems:
- The vulnerability can be used to directly access non-public
  information that either reveals further security relevant problems or
  contains user data, credentials, or sensitive data in general.
- The vulnerability can be used to disrupt the orderly operation of a
  service (Denial of Service).
- The vulnerability can be used to manipulate data within the service.
- XSS, CSRF, RCE, authentication/authorization bypass, SQL inections,
  etc are considered relevant.

We will consider a vulnerability report most likely as NOT relevant if
it reports one of the following problems:
- Missing security features, for example HTTP headers
- Publicly accessible version strings of used software.
- Security vulnerablities that can only be used within the scope of the used account.
- The issue is not exploitable in a realistic szenario.

## 4. Reporting Vulnerabilities

Report vulnerabilities at https://github.com/KittyCAD/cvd/security/advisories/new

Please make sure that you include the following information:
- Which service is affected?
- What is the bug?
- Which steps are required for reproducing the bug?
- How can the bug be exploited?
- What is the impact and risk for Zoo?

Reports will be answered within 72 hours. If you have not received an
answer within that time frame, feel free to contact us again.

The email security@zoo.dev must only be used for general security related inquires.
Do not use this email to disclose security vulnerabilities.

## 5. Bug Bounties / Vulnerability Rewards

The amount of reward payed depends on the severity of the found
vulnerability. We usually do not pay rewards if vulnerabilities can be
found using automated scans scans with of-the-shelf software.

Only responsible disclosures are eligible for rewards.
