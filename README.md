# AttestaBot :fr:

**AttestaBot** is a telegram bot to generate quick & retroactive PDF certificates during
the 2020 french pandemic lockdown.

When it is online, you can find it [@attestabot](https://t.me/attestabot).

<p align="center">
  <a href="https://i.imgur.com/xuRg8hQ.png">
  <img src="https://i.imgur.com/xuRg8hQ.png" alt="drawing" height="400px"/>
  </a>
</p>

## Installation

Once you have you telegram bot username and token you can launch it via the command line :
```bash
# install the required packages. 
python3 -m pip install -r requirements.txt

# launch the bot.
python3 attestabot.py
```

## Getting Started

This bot has 5 commands :
* */help* display the list of commands.
* */profile* register your information for quick generation.
* */generate* create a certificate with custom motives and timestamp.
* */presto* create a one-click retroactive certificate for quick use.
* */cancel* to stop any current commands. 

When you start the application you first need to generate a profile via the `/profile`
command, then use either `/generate` or `/presto` to generate your certificate.

When the user ask for a non immediate timestamp (as by using the `/presto` command) a slight noise
is add to time shift claim.. for organic lifeness and fun :leaves:

## Acknowledgement

This bot is based on the Certificate PDF generator from @tdopierre and @Apoptoz :
[AttestationNumeriqueCOVID-19](https://github.com/Apoptoz/AttestationNumeriqueCOVID-19)

And heavily relied on the wonderful [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot).

## License

*AttestaBot* is released under the **GNU General Public License v3.0**, mainly to assert the non-use of data processed by it :)
