# Contributing

Contributions are **welcome** and will be fully **credited**.

We accept contributions via Pull Requests on [Github](https://github.com/AspirePress) to the appropriate package.

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

## General Rules For Contributing

We welcome contributions. We encourage anyone who wants to contribute to do so. These rules outline our policies in
accepting contributions.

1. Always fork the repository to your own GitHub profile, and do your work in branches there. Do not push branches
   directly to the AspirePress repository, even if you have access to do so. Note that branches related to releases is
   perfectly acceptable
2. To contribute your patch, please open a Pull Request, even if you have access to push to `main`. Since you're likely
   doing your work in your own fork, this makes a pull request more essential.
3. Please make sure your code passes CI/CD before creating a pull request. You can run `make check` locally on most
   repositories to ensure that they comply with our style, quality and test coverages.
4. Please honor and follow our style guidelines.
5. Please do not merge your own Pull Request. Allow it to be merged by the reviewer once review is complete, or the
   review has been approved. **If you push new changes after review is approved, it must be reviewed again!** Project
   leads *may* merge their own pull requests, but are highly encouraged to seek review from the community, first.
6. Please take feedback seriously, if it's offered. We won't generally reject a pull request on spec, and we will often
   offer feedback as to why we don't think it's a good fit or what needs to change. If you honor our feedback, we're
   more
   likely to accept your pull request.
7. Remember that this is a) an open-source project run by volunteers and b) an open-source project that you are welcome
   to fork or work with under the terms of the license. Please feel free to use the code, fork the project, or do what
   you like, especially if we can't incorporate your recommendations. But please also honor
   our [Governance Rules](GOVERNANCE.md).

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