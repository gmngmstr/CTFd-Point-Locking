CTFd_LockingChallenges
======================
This [CTFd](https://ctfd.io/) plugin provides a "locking" challenge type which prevents teams from viewing challenges until they have the necessary points required by the challenge. By locking challenges, it is possible to force teams to attempt challenges across different categories and encourage collaboration.

## Install
Clone this repository into the CTFd plugins folder \
Change the name to `ctfd_lockingChallenges` if needed

## Notes
* Teams can still access uploaded files, even on locked challenges. As a workaround, use 7z or similar to encrypt the challenge file, and include the passphrase in the challenge text.

Original owner [kn0](https://github.com/kn0/ctfd_lockingChallenges)