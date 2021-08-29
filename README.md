# Practitest Firecracker Orb

[![CircleCI Build Status](https://circleci.com/gh/PractiTest/firecracker-orb.svg?style=shield "CircleCI Build Status")](https://circleci.com/gh/PractiTest/firecracker-orb) [![CircleCI Orb Version](https://badges.circleci.com/orbs/practitest/firecracker.svg)](https://circleci.com/orbs/registry/orb/practitest/firecracker) [![GitHub License](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/PractiTest/firecracker-orb/master/LICENSE) [![CircleCI Community](https://img.shields.io/badge/community-CircleCI%20Discuss-343434.svg)](https://discuss.circleci.com/c/ecosystem/orbs)

And orb to execute Firecracker tool that will update CircleCi test results into PractiTest.

## Resources

[Firecracker terminology](https://www.practitest.com/help/methodology-tips/firecracker/) - Firecracker terminology, will help you to understand what is Firecracker all about.

[Firecracker UI](https://firecracker-ui-prod.practitest.com/) - Firecracker UI that will help you to create your configure.

[Firecracker Git](https://github.com/PractiTest/practitest-firecracker) - Firecracker git for local testing and additional information.

For more information contact our support.

## Important!!

In case you don't run your circleci as machine user or don't have java on the image you use you will need to add those lines as a step:
~~~
- setup_remote_docker:
            version: 19.03.13
~~~
**before** you run your tests (in case they fail).