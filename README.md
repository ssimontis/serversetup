# Ansible Collection - ssimontis.serversetup

*serversetup* is a collection of Ansible roles designed to make life easier for
developers who suddenly find themselves becoming system administrators overnight,
or for homelab enthusiasts who want to get some or all of their lab setup ready
to experiment with minimal trial and error.

## Prerequisites
- Python 3 (I use Python 3.9.0 and make no guarantees about compatibility with other versions)
- Ansible 2.10.4
- Ansible-lint 4.3.7

## Project Setup
Do the equivalent of this, roughly.
- Install Python build dependencies
- Install pyenv and pyenv-virtualenv
- Create a 3.9.0 virtual environment for Python
- Install the ansible[lint] gem

## Support
The issue tracker on Github is the best place to go if you need assistance with
this collection. I cannot guarantee a timely response to all inquiries; if you
have a time-sensitive support issue or feature request, or are interested in my
consulting abilities, please [send me an introductory e-mail](mailto:yo@scottsimontis.io) and we can discuss your specific needs.

## Contributing
Help is always welcome. You don't have to be an Ansible expert, assistance writing
documentation, testing the roles on different host configurations, or answering
questions from other users is always immensely appreciated.

If you are thinking of adding a role or making significant changes to an existing role,
I ask that you please open an issue to discuss your feature before beginning your implementation. 
I would hate for you to spend a significant amount of time developing a role that is not in
line with the project's vision.

Bonus points if you can provide some documentation detailing the justification for
your changes, a brief outline of how you are going to approach the objective, or the
shell script you are using as inspiration.

Please lint your code and provide tests of some sort to verify that the changes work as expected. 
Code that does not pass the linter or fails to achieve the desired results will be rejected
until the submitter is able to correct the issues.

## License
This project is licensed under the MIT License, which you can read within this repo's LICENSE.md file.
