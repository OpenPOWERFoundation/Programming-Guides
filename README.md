# Programming Guides for Linux on Power
This project contains documentation helpful to application developers
for Linux on OpenPOWER systems.  The following documents are 
contained:

- *Linux on Power Porting Guide: Vector Intrinsics* -- A guide to porting
   x86 vector intrinsics to the OpenPOWER processor. The online 
   version of the document can be found in the OpenPOWER Foundation
   Document library at [TBD](http://openpowerfoundation.org/?resource_lib=TBD).
   
- *Intrinsic Function Programming Reference* -- A document detailing
  the various vector intrinsics on the OpenPOWER processor.  This document
  is just beginning to be created.

To build this project, one must ensure that the Docs-Master project has
also been cloned at the same directory level as the Programming-Guides project.
This can be accomplished with the following steps:

1. Clone the master documentation project (Docs-Master) using the following command:

  ```
  $ git clone https://github.com/OpenPOWERFoundation/Docs-Master.git
  ```
  
2. Clone this project (Programming-Guides) using the following command:

  ```
  $ git clone https://github.com/OpenPOWERFoundation/Programming-Guides.git
  ```
  
3. Build all the documents withing the project with these commands:
  ```
  $ cd Programming-Guides
  $ mvn clean generate-sources
  ```

The project which controls the look and feel of the document is the 
[Docs-Maven-Plugin project](https://github.com/OpenPOWERFoundation/Docs-Maven-Plugin), an 
OpenPOWER Foundation private project on GitHub.  To obtain access to the Maven Plugin project, 
contact TSC Chair of the OpenPOWER Foundation \([tsc-chair@openpowerfoundation.org](mailto://tsc-chair@openpowerfoundation.org)\) or 

## License
This project is licensed under the Apache V2 license.  More information
can be found in the LICENSE file or online at

  http://www.apache.org/licenses/LICENSE-2.0

## Community
To comment on, propose changes, and engage in community dialogue, you can open issues 
in the [Project Issues](https://github.com/OpenPOWERFoundation/Programming-Guides/issues) or post to
the community mailing list \([syssw-programming-guides@mailinglist.openpowerfoundation.org](mailto://syssw-programming-guides@mailinglist.openpowerfoundation.org)\).

## Contributions
To contribute to the project, post patches to the community mailing list 
\([syssw-programming-guides@mailinglist.openpowerfoundation.org](mailto://syssw-programming-guides@mailinglist.openpowerfoundation.org)\)
where they will be reviewed and approved when ready.

Contributions to this project should conform to the `Developer Certificate
of Origin` as defined at http://elinux.org/Developer_Certificate_Of_Origin.
Commits to this project need to contain the following line to indicate
the submitter accepts the DCO:
```
Signed-off-by: Your Name <your_email@domain.com>
```
By contributing in this way, you agree to the terms as follows:
```
Developer Certificate of Origin
Version 1.1

Copyright (C) 2004, 2006 The Linux Foundation and its contributors.
660 York Street, Suite 102,
San Francisco, CA 94110 USA

Everyone is permitted to copy and distribute verbatim copies of this
license document, but changing it is not allowed.


Developer's Certificate of Origin 1.1

By making a contribution to this project, I certify that:

(a) The contribution was created in whole or in part by me and I
    have the right to submit it under the open source license
    indicated in the file; or

(b) The contribution is based upon previous work that, to the best
    of my knowledge, is covered under an appropriate open source
    license and I have the right under that license to submit that
    work with modifications, whether created in whole or in part
    by me, under the same open source license (unless I am
    permitted to submit under a different license), as indicated
    in the file; or

(c) The contribution was provided directly to me by some other
    person who certified (a), (b) or (c) and I have not modified
    it.

(d) I understand and agree that this project and the contribution
    are public and that a record of the contribution (including all
    personal information I submit with it, including my sign-off) is
    maintained indefinitely and may be redistributed consistent with
    this project or the open source license(s) involved.
```

