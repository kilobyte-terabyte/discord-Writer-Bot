<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]

[![Issues][issues-shield]][issues-url]
[![ClosedIssues][closed-issues-shield]][closed-issues-url]
[![PR][open-shield]][open-url]
[![ClosedPR][closed-shield]][closed-url]

[![Discord][discord-shield]][discord-url]
[![buddy pipeline](https://app.buddy.works/cmrwarwicker-1/discord-writer-bot/pipelines/pipeline/292118/badge.svg?token=87093bfb15df4a9419bd2cd31863b95c6d87bc38fa56051468bb0d8c90f26780 "buddy pipeline")](https://app.buddy.works/cmrwarwicker-1/discord-writer-bot/pipelines/pipeline/292118)

<br />

[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://www.python.org)

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/cwarwicker/discord-Writer-Bot">
    <img src="https://images.discordapp.net/avatars/460090810029965312/1baab409193652b27ce7d30d1a6ecc7a.png?size=512" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Writer Bot</h3>

  <p align="center">
    Writer-Bot is a discord bot for writing-based servers.
    <br /> 
    It has many features, such as writing sprints, word count goals, xp/levels, prompts and random generators
    <br />
    <a href="https://github.com/cwarwicker/discord-Writer-Bot/issues">Report Bug</a>
    ·
    <a href="https://github.com/cwarwicker/discord-Writer-Bot/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Bot Usage](#bot-usage)
* [Roadmap](#roadmap)
* [Development](#development)
* [Contributing](#contributing)
* [License](#license)
* [Credits](#credits)



<!-- ABOUT THE PROJECT -->
## About The Project

Writer Bot began life as a small project for one writing server on discord of which I was a member. We were using a sprint bot, but I thought it would be quite handy to have more functionality, so decided to make my own bot for the server to use. This original version of the bot was written in node.js, using the discord.js library.

After releasing it to that server, as an after-thought I decided to add it to one of the discord bot lists, in case anyone else found it useful.

The bot soon became quite popular, being added to hundreds, then thousands of servers, and it became quite apparent that the way I had made it, just wasn't suited to lots of servers and there were lots of problems. So I decided to re-write the entire thing in Python instead and try to make it function better across multiple servers.

At the time of writing this, the bot is now in over 7000 servers and (for the most part) is going strong.


<!-- USAGE EXAMPLES -->
## Bot Usage


**Writing-related commands**

`!ask`: Asks you a random question about your character or your world, to get the creative juices flowing.

`!challenge`: Generates a random writing challenge for you. e.g. "Write 400 words in 15 minutes". You can add the flags "easy", "normal", "hard", "hardcore", or "insane" to choose a pre-set wpm, or add your chosen wpm as the flag, or you can specify a time instead by adding a the time in minutes, e.g. "15m"

`!event`: Create server-wide writing events and compete against your fellow writers to see who can write the most

`!generate`: Random generator for various things (character names, place names, land names, book titles, story ideas). Define the type of item you wanted generated and then optionally, the amount of items to generate.

`!goal`: Sets a daily goal which resets every 24 hours

`!project`: Using these commands, you can create different projects and store word counts against them seperately. They also integrate with the wrote and sprint commands. See the help information for those commands for more info.

`!sprint`: Write with your friends and see who can write the most in the time limit!

`!wrote`: Add to your total words written statistic

**Fun commands**

`!8ball`: Ask the magic 8-ball a question. Your question will be routed to a text-processing AI and broken down into character sets, in order to properly analyze the content of the question and provide a meaningful answer.

`!flip`: Flips a coin

`!quote`: Gives you random motivational quote

`!reassure`: Gives you reassurance/motivation

`!roll`: Rolls a dice between 1-6, or 1 and a specified number

`!xp`: Checks your server Experience Points and Level. Use the "top" flag to see the top 10 on this server.

**Utility Commands**

`!about`: Shows bot information and status

`!help`: Display help information about the bot and its commands

`!invite`: Generates an invite link to invite the bot to another server

`!mysetting`: Allows you to set user configuration values, such as your timezone

`!ping`: Ping the bot to check the latency

`!profile`: Displays your user statistics

`!reset`: Allows you to reset your stats

`!setting`: Allows users with the (MANAGE_MESSAGES) permission on the server, to change configuration values




<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/cwarwicker/discord-Writer-Bot/issues) for a list of proposed features (and known issues).

<!-- Development -->
## Development

To get a local copy of Writer Bot up and running, please see the separate [Writer Bot Development Environment](https://github.com/cwarwicker/discord-Writer-Bot-env) repo.



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the [Development Environment](https://github.com/cwarwicker/discord-Writer-Bot-env) project
2. Create your Feature Branch in the `app` submodule (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the GNU General Public (V3) License. See `LICENSE.txt` for more information.


<!-- Credits -->
## Credits

Thank you to everyone who gets involved in helping out with Writer Bot, whether that is writing code, translating language strings, answering questions on the support server, or even just using the bot! Without you, Writer Bot would just be some code sitting on a server doing nothing.

**Code Contributors**

https://github.com/cwarwicker/discord-Writer-Bot/graphs/contributors

**Translators**

kdem - French Translations 


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/cwarwicker/discord-Writer-Bot.svg?style=flat-square
[contributors-url]: https://github.com/cwarwicker/discord-Writer-Bot/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/cwarwicker/discord-Writer-Bot.svg?style=flat-square
[forks-url]: https://github.com/cwarwicker/discord-Writer-Bot/network/members
[stars-shield]: https://img.shields.io/github/stars/cwarwicker/discord-Writer-Bot.svg?style=flat-square&color=brightgreen
[stars-url]: https://github.com/cwarwicker/discord-Writer-Bot/stargazers
[issues-shield]: https://img.shields.io/github/issues/cwarwicker/discord-Writer-Bot.svg?color=orange&style=flat-square&label=open%20issues
[issues-url]: https://github.com/cwarwicker/discord-Writer-Bot/issues
[discord-shield]: https://img.shields.io/discord/503593039541960704?logo=discord
[discord-url]: https://discord.com/invite/awaC6Vq
[closed-shield]: https://img.shields.io/github/issues-pr-closed-raw/cwarwicker/discord-Writer-Bot?color=purple&style=flat-square
[closed-url]: https://github.com/cwarwicker/discord-Writer-Bot/pulls?q=is%3Apr+is%3Aclosed
[closed-issues-shield]: https://img.shields.io/github/issues-closed-raw/cwarwicker/discord-Writer-Bot?color=purple&style=flat-square
[closed-issues-url]: https://github.com/cwarwicker/discord-Writer-Bot/issues?q=is%3Aissue+is%3Aclosed
[open-shield]: https://img.shields.io/github/issues-pr/cwarwicker/discord-Writer-Bot?color=orange&style=flat-square
[open-url]: https://github.com/cwarwicker/discord-Writer-Bot/pulls