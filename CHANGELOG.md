commit 0947e794f3d273265869b7e727676336dee0a28e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Sep 24 12:50:18 2020 -0400

    Added SSHD role

commit 78720f5f6d938dc3d414a4aae8fbdb696df7043f
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Sep 24 12:25:34 2020 -0400

    Added rsyslog role

commit 06496b7ad4e43e33da3cd3b55693bed3ac1e02f7
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Sep 24 12:11:18 2020 -0400

    Updated base role to latest

commit dd2bbe00616b00a7bb5c31d890d6cc8b3307d855
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Sep 24 11:28:26 2020 -0400

    Added base role Molecule testing

commit 70ec811ead74713a73e8b50746c35d96ff57f526
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Sep 24 11:27:10 2020 -0400

    Added base and manage LVM roles

commit 3893e538680caea54e1b36d4d61ec2721c78a601
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Sep 24 11:16:23 2020 -0400

    Added configure_postfix: true
    
    - This resolves issues with RedHat tests for Postfix
    - Ensures that Postfix service starts

commit 01f9b8b3c4045c0dde10cdd406e0af2848cb1c37
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Sep 24 10:55:51 2020 -0400

    Added Postfix role

commit 16ce4ff0e4b990dd4b0e74178929a46beaf992f3
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Sep 24 10:42:22 2020 -0400

    Disabled CentOS 8 NTP role testing
    
    - CentOS8 uses chrony

commit 01fa02b3c37bfa045189e2ba31d3a7548eddd915
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Sep 24 10:31:05 2020 -0400

    Updated NTP role to latest submodule

commit 69cfd268752af844ec4cdfb1c4a9186199492a4b
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Sep 24 09:16:54 2020 -0400

    Disabled Debian 8 testing
    
    - Ansible 2.10.x requires Python 3.5+ and Debian8 by default only supports 3.4
    
    - Will revisit this if there is a need

commit 8e05455f4b9d8850e9cb664264e0abf40e8083a7
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Sep 24 01:07:59 2020 -0400

    Updated Molecule playbook to include motd and ntp roles

commit eaa647972926f95ff0d3982327dff988655b41cf
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Sep 24 01:04:17 2020 -0400

    Updated Python requirements

commit d0f2cb6ab17871d762f399e25feede218550c95c
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Sep 24 01:04:01 2020 -0400

    Added Python reqs as trigger for CI
    
    This will ensure that if Python reqs are updated, all CI workflows are validated

commit f20d29ddded782581b78118106ad9e0b6c7e1b4d
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Thu Sep 24 00:53:08 2020 -0400

    Added NTP role

commit 1126141b2a0bfca7b89eb86a2d11a10529921bf6
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Sat Sep 19 02:05:13 2020 -0400

    Added motd role to pipeline, etc.

commit 2c60deff8e8a69f06a074a63d0fa2b63dab5c153
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Sep 18 22:46:44 2020 -0400

    Updated workflows to account for submodules

commit c49ae5ae431f27159e8d3bd6e62c8d29c4251a21
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Sep 18 22:45:17 2020 -0400

    Testing submodule changes triggering workflows once more

commit 8ae254c893d11a03b33b57ba25d61e89b0a65f04
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Sep 18 22:36:27 2020 -0400

    Testing submodule changes triggering workflows

commit 24e24e167f8b48943c9d4b20003b7489a3a94fa4
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Sep 18 22:11:23 2020 -0400

    Updated submodule for chrony role to latest for fixes

commit 8b846656ec6253a80762ba80a75c525c02622ef4
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Sep 18 18:29:31 2020 -0400

    Added chrony role and build status

commit cda57fae7c33318947a94635808eca7f4079dc9b
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Sep 18 18:28:14 2020 -0400

    Added chrony role workflow testing

commit 496da6f0d95cbe6cd450e48bc7347bee07d93434
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Sep 18 18:18:43 2020 -0400

    Disabled apt_sources backports for testing

commit a6b463169e0c47fb4148788d855448b01226f2f6
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Sep 18 17:26:45 2020 -0400

    Updated repo info to begin including role build status badges

commit f982bef4488025b3667e08262ceaf2efdccc9eaa
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Sep 18 17:21:33 2020 -0400

    Updated workflow names to match Ansible collection role

commit b437cb3369ed0d306b335c44ce2b4c3ec7f097e7
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Sep 18 17:14:00 2020 -0400

    First commit to test apt_sources role

commit c76b3e89b59f42cd351ce1d2da9d174b152da05e
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Sep 18 17:13:38 2020 -0400

    Added path to GitHub repo for SCM

commit 6a444776783a0840c87b108f5e61e8968d8164f2
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Sep 18 16:58:13 2020 -0400

    Added submodules checkout

commit 47263348db8151f328f8510d0fb19f24381fad86
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Sep 18 16:48:52 2020 -0400

    Added environment setting for path to Ansible roles for Molecule

commit e0be77844a5818a399f3322040ae99134474fee6
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Sep 18 16:35:32 2020 -0400

    Previous workflow didn't work
    
    Added quotes around paths, but...

commit 95d8851e16c764fce8358e72295a3b2342d04392
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Sep 18 16:28:18 2020 -0400

    First testing of consuming roles as submodules for collections
    
    This will test GitHub Actions as well

commit 9ba29776ada3532c565e78825abf294034ad121b
Author: Larry Smith Jr <mrlesmithjr@gmail.com>
Date:   Fri Sep 18 13:58:11 2020 -0400

    First commit using Cookiecutter Template
