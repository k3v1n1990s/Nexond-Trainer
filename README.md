# Nexon'd Trainer
A Universal MapleStory Trainer

This trainer is currently in Beta development stage. The goal of this trainer is to provide a highly user-customizable and user-friendly experience. This trainer will be heavily based off of [Simple Trainer](https://github.com/md35-gk/Simple-Trainer).

## Planned Features
See the development here: [Nexon'd Trainer Project](https://github.com/md35-gk/Nexond-Trainer/projects/1)

Nexon'd Trainer should have the following implemented before it's official release to the public:
* Basic hacks, a profile system, ID search tool
* Backwards compatibility through the use of a GitHub-powered Script Bank
  * The trainer will allow users to enter their own custom GitHub Script Bank if they so choose
  * Due to this, the trainer may no longer be able to provide auto ban warnings to certain hacks. Determining a workaround
  * With this being on GitHub, anyone can submit script updates as needed -- ultimately creating the first(?) community-updated trainer. (Those with high knowledge in updating scripts can request to become a Contributor, in which they may merge pull requests and update scripts directly)
* ~~A Log file will be implemented to detail occurring trainer events~~ done!
* ~~An in-trainer settings tab will be provided to allow users to directly edit trainer details, such as the Script Bank URL~~ done!

## Known Issues
* Loading the trainer each time causes a ~5 second application freeze as it retrieves scripts. No workarounds.
* Failure to connect to GitHub (on the end user's side or GitHub's servers) will render the trainer useless. A user-sided script loading will be implemented in the future.

## Expected Release
This trainer, as successor to Simple Trainer, will take much more work and is currently in Open Beta. There is no ETA for an official release.

## Current Progress
As of 2/2/18, trainer settings has been implemented and the implementation of GitHub retreival and script checks are being worked on.

As of 3/10/18, script checks and loading has been implemented. Working on an early UI and expected Beta release for MSEA is set late March.

As of 3/15/18, v0.1 BETA was released with support for MSEA.
