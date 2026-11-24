# Security Policy for the perl-workflow organisation

Report security issues privately via the "Report a vulnerability" button on the
affected repository's **Security** tab, or by e-mail to `<SECURITY-CONTACT-EMAIL>`.

This is the default Security Policy for all repositories in the
[perl-workflow](https://github.com/perl-workflow) GitHub organisation that do
not have their own `SECURITY.md`.

Repositories that ship a CPAN distribution, such as
[Workflow](https://github.com/perl-workflow/perl-workflow), include their own
policy in the root of the repository and the distribution. That policy takes
precedence over this one.

This text is based on the CPAN Security Group's Guidelines for Adding a Security
Policy to Perl Distributions (version 1.5.0)
<https://security.metacpan.org/docs/guides/security-policy-for-authors.html>

## How to Report a Security Vulnerability

Security vulnerabilities can be reported to the current maintainers in one of
two ways:

- **GitHub private vulnerability reporting (preferred):** go to the affected
  repository's **Security** tab, open **Advisories** and click the
  "Report a vulnerability" button.
- **E-mail:** `<SECURITY-CONTACT-EMAIL>`, if you do not have, or do not
  want to use, a GitHub account.

Please state which repository (and, for CPAN distributions, which version) is
affected, and include as many details as possible, such as code samples or test
cases, so that we can reproduce the issue. Check that your report does not
expose any sensitive data, such as passwords, tokens or personal information.

If you would like any help with triaging the issue, or if the issue is being
actively exploited, please copy the report to the CPAN Security Group (CPANSec)
at <cpan-security@security.metacpan.org>.

Please *do not* use public issue trackers, pull requests or discussions for
reporting security vulnerabilities.

Please do not disclose the vulnerability in public until past any agreed date
for public disclosure, or until it has been made public by the maintainers or
CPANSec. That includes patches and pull requests.

For more information, see
[Report a Security Issue](https://security.metacpan.org/docs/report.html)
on the CPANSec website.

## Response to Reports

The maintainers are volunteers and aim to acknowledge your security report as
soon as possible. If you have not received a response within one week, please
send a reminder to the maintainers and copy the report to CPANSec at
<cpan-security@security.metacpan.org>.

The initial response will be an acknowledgement, possibly with a request for
more information. It will not necessarily include a fix.

The maintainers may forward the report to the security contacts of other
projects where it is relevant, such as prerequisite modules, system libraries
or downstream software, and to CPANSec.

Confirmed vulnerabilities will be fixed in a new release, and published as a
GitHub Security Advisory on the affected repository. For CPAN distributions a
CVE will be requested via CPANSec where appropriate. Reporters will be credited
in the advisory and the changelog, unless they ask not to be.

## What This Policy Applies To

This policy covers the software and content maintained in the repositories of
the perl-workflow organisation, including the project website.

Security vulnerabilities are considered anything that allows users to execute
unauthorised code, access unauthorised resources, or to have an adverse impact
on accessibility or performance of a system.

Vulnerabilities in upstream software (prerequisite modules, system libraries,
Perl itself or third-party services) are not covered, unless they affect our
software or our software can be used to exploit them. Vulnerabilities in
downstream software that uses our distributions are not covered.

### Supported Versions

Unless a repository's own policy says otherwise, only the latest release of
each distribution is supported for security fixes. The maintainers may raise the
minimum required version of Perl or of a prerequisite module in order to fix a
security issue.
