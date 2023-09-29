# DASL - The Decoupled Authentication and Security Library for PHP
*Version 0.1.0*

[![Project Status: Concept – Minimal or no implementation has been done yet, or the repository is only intended to be a limited example, demo, or proof-of-concept.](https://www.repostatus.org/badges/latest/concept.svg)](https://www.repostatus.org/#concept) ![Required PHP Version](https://img.shields.io/badge/PHP-%3E%3D7.0-critical) ![License](https://img.shields.io/github/license/alarm-siren/dasl) ![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/alarm-siren/dasl) ![Downloads](https://img.shields.io/github/downloads/alarm-siren/dasl/total)

DASL is a simple library for PHP that takes the heavy-lifting out of user authentication, session management and permissions. Insofar as reasonably possible, this library been designed not to make any assumptions about your application and thus maintain flexibility and extensibility, whilst also having sane defaults and built-in functionality that covers the most common use cases.

## Dependencies
This library has the following dependencies:
- PHP 7.0 or greater.
- *To Do* Required PHP extensions, if any.
- A supported data storage back end (PDO-supported database or flat file)

## Comments, Requests, Bugs & Contributions
All are welcome!
Please open an [Issue](https://github.com/Alarm-Siren/dasl/issues) or [Pull Request](https://github.com/Alarm-Siren/dasl/pulls), as appropriate.

## Library Installation
*To Do*

## Donations

I really hope you've found this library useful. If you'd like to buy me a beer in thanks for the work I put into it, you can make a donation using the button below:

[![paypal](https://www.paypalobjects.com/en_GB/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=UX25HM4CZFFWW)

## License & Legal
DASL - The Decoupled Authentication and Security Library for PHP.
Copyright 2009-2023, [Nicholas Parks Young](https://github.com/Alarm-Siren).

This library is free software; you can redistribute it and/or modify it under the terms of the [GNU Lesser General Public License as published by the Free Software Foundation; either version 2.1 of the License](https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html), or (at your option) any later version.

You should have received a copy of the GNU Lesser General Public License along with this library; if not, write to the Free Software Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA, 02110-1301, USA.

### Warranty Disclaimer

This library is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the [GNU Lesser General Public License](https://www.gnu.org/licenses/old-licenses/lgpl-2.1.en.html) sections 15 and 16 for more details.

## FAQ

Answers to some common questions about this library.

### Is this library in active development?

Yes. Obviously its not done yet, but I am working on it when time allows.

### Why did you make this? Every web framework includes similar functionality!

I don't like using heavy web framework such as CakePHP, Laravel and Symfony, and I assume I cannot be the only one. I understand why they exist, and I understand why many PHP programmers like to use them. That's fine - if you want a heavy web framework, or already use one, then DASL is not for you. However, for people like me who prefer not to use them, I have created this library as a totally decoupled component that doesn't drag you into a wider ecosystem.

### Have you got any plans to make other decoupled libraries?

I vaguely have plans to create a Routing framework and an Email Management library, but I want to get DASL done first. If I do create any additional libraries I will make sure that, whilst they will work well together, they will not be dependent on each other.

### Are there any other decoupled libraries you recommend?

Yes! I like the [Smarty Template Engine](https://www.smarty.net/), which I use extensively in my own web projects.
