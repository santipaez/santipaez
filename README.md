# Santiago Páez

Infrastructure and cloud engineer on the Microsoft stack. I administer Microsoft 365,
Entra ID and Azure for enterprise clients, and I build the software that operates them.

San Rafael, Mendoza, Argentina

## What I work on

Two small projects, both about the same question: where does a control belong, and what
happens when it sits in the wrong place.

**[permission-rag](https://github.com/santipaez/permission-rag)** — access control applied
during retrieval, before a model ever sees a document. Ships an eval suite that fails the
build on any leak, and a benchmark measuring what the opposite order costs: recall falls
from 100% to 37% once 20 restricted near-duplicates compete per topic.

**[web-posture](https://github.com/santipaez/web-posture)** — passive security posture
checks for a domain: DMARC and SPF policy, TLS, security headers, cookie flags and exposed
files. Standard library only, 23 offline tests, and an authorization gate that refuses to
scan without an explicit flag and a recorded reason.

## Day to day

Microsoft 365, Entra ID, Intune, Windows Autopilot, Conditional Access and Azure Virtual
Desktop for enterprise clients, alongside servers, NAS, firewalls and backup. Python and
TypeScript when something needs building rather than fixing.

## Elsewhere

[LinkedIn](https://linkedin.com/in/spaezredondo) · [spaezredondo@gmail.com](mailto:spaezredondo@gmail.com)
