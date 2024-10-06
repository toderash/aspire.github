# Contributing

Contributions are **welcome** and will be fully **credited**.

We accept contributions via Pull Requests on [Github](https://github.com/AspirePress) to the appropriate package.

## Versioning

This project uses [Semantic Versioning](https://semver.org/) for all packages, libraries and plugins.

## Pull Requests

### WordPress Plugins & Projects

For WordPress Plugins and Projects, we ask that you follow these standards:

* Use the [WordPress Coding Standard](https://developer.wordpress.org/coding-standards/wordpress-coding-standards/). You
  can automate this with [PHPCS](https://github.com/WordPress/WordPress-Coding-Standards), and we recommend you do.
* We ask (but do not require) that you write tests for your contributions. We understand that unit testing the WordPress
  framework is difficult.
* Please document any changes in behavior inside the pull request so we can easily update the CHANGELOG when we release
  a new version.
* If your changes break backwards compatibility with the current stable version, it MUST be released as part of the next
  major version. Please target your Pull Request against the branch for the next major version or, if one is not
  created, ask that one be created for you. Additionally, any breaking changes should provide a migration between the
  old version(s) and a new version.
* All code contributed to WordPress-related plugins and projects, *especially* code that touches the GPL'ed WordPress
  code, is subject to the GPL as well, and you agree to license your code under the GPL as a condition of committing and
  merging your code with ours. See the Copyright section below for more.

### For Non-WordPress Libraries & Components

For non-WordPress repositories (e.g. libraries and components that are tangential but do not call into WordPress core),
we apply the following standards:

* We use the [Laminas Coding Standard](https://docs.laminas.dev/laminas-coding-standard/) with certain rules turned off.
* We require tests to be written for code that you commit, and we encourage you to run the tests prior to opening a pull
  request.
* We require that the code you submit pass PHPStan Level 6 or higher.
* Please document changes you make to the CHANGELOG inside each project, so we know what changes were made, and use that
  information in your Pull REquest.
* Please be sure to document the WHY of your request, not just the WHAT. For example, "Changed class to be more
  readable" is not a good commit message. "Changed class to be more readable" followed on another line by "The Foo class
  was hard to read due to some complex logic. I simplified the logic by implementing a bubble sort algorithm, which
  reduced the complexity and improved the readability" is a much clearer message.
* Please try to keep the first line of your commit message to 80 characters or less, and use subsequent lines to
  communicate additional information.
* Pull requests should be 10 or fewer files and +/- 500 lines of code. If yours exceeds this, we will want you to
  explain why, and we may ask you to break up the request into logical parts.
* If your change breaks backwards compatibility, please target the next major version branch. If one has not been
  created, request that we create it for you. We cannot accept backwards-compatibility breaking changes in the current
  version, as this violates Semantic Versioning.
* All code contributed is subject to the license of the repository to which it is contributed. You agree to release your
  code under that license.

## Maintenance Cycle

Every major version released will be maintained, unless we mark the project as abandoned. If we mark a project as
abandoned, we will grant at least six months notice prior to the end of support.

When a new major version is released, we will offer security fixes and patches to the old version for one year following
the release of the new version. For example, if 1.0 is replaced by 2.0, we will continue to support 1.0 with security
and patches for 1 year following the release of 2.0.

For minor and patch (<major>.<minor>.<patch>) versions, we offer no ongoing support of an old minor or patch version
once a new one has come out. Because we follow semantic versioning, we will not break compatibility of the major version
in a minor or patch release.

The exception to this policy is in an emergency where security or safety is at risk. If a security issue requires
breaking backwards compatibility, we will a) inform users through our communication channels and b) make the minimum
number of changes required to patch the problem. We may also revoke access to versions that contain severe security
vulnerabilities. Finally, we will prepare to release a new major version as quickly as possible containing the breaking
changes.

## Licenses and Copyrights

If you contribute to this project, you grant an exclusive,royalty-free, global, irrevocable license to AspirePress and
any members of AspirePress to use, relicense, redistribute, copy, modify, change or otherwise utiize any source code you
contribute. Furthermore, contribution of source code is not a guarantee that you will be granted rights to use the
project for your own purposes. By contributing you acknowledge that the code you contribute becomes licensed by
AspirePress, that you may not revoke that license, and you may not use that code again without written permission from
AspirePress.

You also agree to indemnify and hold harmless AspirePress and any members of AspirePress from any harm, including
litigation or copyright enforcement, for code you commit that you do not own. **DO NOT COMMIT CODE YOU DO NOT OWN OR
THAT IS COPYRIGHTED BY SOMEONE ELSE!**

For libraries that are not CopyLeft (e.g. GPL, LGPL, AGPL, etc.) AspirePress permits all open-source licenses to be
used, except for CopyLeft licenses. You may contribute open source code that does not implement these licenses. If a
particular library or repository is already licensed under a CopyLeft license, you may use code from these license
types.

Your license of your contributions to AspirePress relieves us of the right to relicense any project or repository under
new terms, starting with the next major version. However, we voluntarily limit our relicensing right to relicensing
projects only insofar as the new license is no more restrictive than the previous license. We reserve the right to
convert any non-CopyLeft licensed code into a CopyLeft-licensed project, though we will use this right sparingly. You
agree that your permission is not needed for relicensing of a project that you contributed to.

Note that we may "dual license" any project at any time. A "dual license" may require certain users to use a particular
license based on conditions within that license; all others may use the original or new (but similarly restrictive)
license. The "dual license" model does not in any way constitute a reduction in rights or freedoms granted users, and
any user that wishes to remain on an older version under the original license may do so. We will not retroactively
change license terms.