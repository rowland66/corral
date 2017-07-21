# Corral

Pony dependency management command-line tool. Corral builds on the work done in pony-stable,
adding a few new things:

   - Using new Pony cli package for command line parsing.
   - Having a complete command set for managing dependency files.
   - Refactored for extensibility.
   - TODO: Support for version constraints on deps.
   - TODO: Support for revision locking on deps, using a lock.json file.
   - TODO: Using the Pony process package for spawning external helpers like Git.

For a discussion of the requirements and design work behind Corral, see:
   - https://docs.google.com/document/d/1c7puEQLks3X1wpabuXxox8Qi1HUhfSwhobUvmVE56Rw/edit#
