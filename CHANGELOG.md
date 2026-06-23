## pw_hash v0.1.3, 2026-06-23

* [internal] Update `md-5` to 0.11, `sha1` to 0.11, `sha2` to 0.11, `blowfish` to 0.10, `hmac` to 0.13.
* [internal] Fix Clippy warnings: literal-bool asserts, manual loop counters.

## pw_hash v0.1.2, 2026-03-24

* [internal] Update `rand` from 0.8 to 0.10, `sha2` from 0.10.8 to 0.10.9, edition to 2024.
* [internal] Get rid of unwraps in favor of `let-else` and `if let` patterns.
* [internal] Fix Clippy warnings: div_ceil, needless borrows, manual swap, range contains, doc formatting, lifetime elision

## pw_hash v0.1.1, 2024-08-01

* Documentation and links updated.

## pw_hash v0.1.0, 2024-08-01

* Fork created.

* [internal] Bump outdated dependencies, replace deprecated `sha-1` with `sha1` ([1f36010](https://github.com/NamesMark/pwhash/commit/1f36010cd03da0c7d1bba90f0eb73ae482e67c39)).

## (pwhash) v1.0.0, 2021-01-03

* Increase the default bcrypt cost to 10, in line with the recent OpenBSD
  value. Technically, this is a breaking change, so the crate version
  should go up.

* [internal] Update for 2018 Edition.

* [internal] Bump outdated dependencies and clean up Clippy warnings ([#15](https://github.com/inejge/pwhash/pull/15)).

* [internal] Move CI to GitHub.

## (pwhash) v0.3.1, 2020-07-08

* [internal] Update dependencies ([#13](https://github.com/inejge/pwhash/pull/13)).

## (pwhash) v0.3.0, 2019-01-13

* [internal] Update dependencies, replace outdated crates ([#11](https://github.com/inejge/pwhash/pull/11)).

## (pwhash) v0.2.0, 2018-05-09

* Widen password input type to [u8] ([#8](https://github.com/inejge/pwhash/issues/8)).

* Warn users who try to generate new insecure hashes by deprecating
  the corresponding hashing funcions ([#8](https://github.com/inejge/pwhash/issues/9)).
  Verification for insecure hashes is not deprecated.

* [internal] Use ? for error handling instead of try!

## (pwhash) v0.1.2, 2017-04-01

* Better compatibility with Unix crypt through the removal of length check
  from `unix::crypt()` ([#3](https://github.com/inejge/pwhash/pull/3)).

## (pwhash) v0.1.1, 2016-02-09

Initial version.
