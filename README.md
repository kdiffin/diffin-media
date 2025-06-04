# Project diffin-media

going to try to clone twitter and discord type shit with templ+htmx

**shit to get done**

- [ ]
- [ ] make the packages not-so-nested
- [ ] get the templ files all organized and stuff, into pages and components
- [ ] componentize frontend
  - [x] make dropdowns have border
- [ ] make an `<AvatarDropdown>` component
- [ ] make navbar have responsivene links to chat/feed, profile dropdown (crud on profile), github repo (footer too)
- [ ] make a profile page:
  - [ ] with dm, chat, and show off a bunch of his stuff in his profile like
  - [ ] most reacted message in chat part, most well rated tweet, followers, following, total likes on profile, total tweets
- [x] change how the replies nest

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## MakeFile

Run build make command with tests

```bash
make all
```

Build the application

```bash
make build
```

Run the application

```bash
make run
```

Create DB container

```bash
make docker-run
```

Shutdown DB Container

```bash
make docker-down
```

DB Integrations Test:

```bash
make itest
```

Live reload the application:

```bash
make watch
```

Run the test suite:

```bash
make test
```

Clean up binary from the last build:

```bash
make clean
```
