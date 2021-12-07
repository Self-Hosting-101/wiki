## Self-Hosting 101

Self-Hosting 101 is a guide made to allow you to host in a secure way, every file, application and online services from home.

It is intended for anyone wishing to set up their own services at home, whether to benefit from various tools for personal projects, to simplify their lives or for more specific reasons such as a desire to have control over their data and no longer depend on GAFAM.


## How it works?

All of the services that need to be ran are intended to be ran in a docker container. There is also Ansible to automate tasks.

So you need Docker, Ansible and a Linux host.


## What is a service?

OK, so a service can be anything that run 24/7. For example it can be a website, a mail server, a video streaming platform, ...

Check this [awesome selfhosted github](https://github.com/awesome-selfhosted/awesome-selfhosted) repo to have a more concrete idea of the types of services you can host.


## Security

The Docker stack follows the principle of exposure minimisation.

There is some hardening rules to secure the server which is based on [CIS guides](https://www.cisecurity.org/).

## Contribute

Feel free to open issues or make pull requests at github.


## Contact

For any question or other feel free to contact me:

- :material-twitter: - [@lambdhack](https://twitter.com/lambdhack)
- :material-discord: - lambdhack#3031
- :material-email: - `lambdhack[AT]lambdhack[dot]bzh`

You can find a presentation (in french) of Self Hosting 101 [here]() and slides are available [here](https://slides.com/lambdhack/deck-5aad03).

## WTFPL License

This project is licensed under the [WTFPL License](https://choosealicense.com/licenses/wtfpl/).
