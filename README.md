# Pedestal-app

Pedestal is a web application framework written in Clojure that aims to bring
both the language and its principles (Simplicity, Power and Focus) to client and
server-side development.  This project is client-side specific.

---
**Status of Pedestal-app:**

This repository is an *archival copy* of the original pedestal-app project. See the Google Group's message ["So what's happening with Pedestal 0.3.0?"](https://groups.google.com/forum/#!topic/pedestal-users/jODwmJUIUcg) for more information.

**We are not actively developing or accepting new features, but we will accept bug fixes submitted by the community.**

If you're interested in carrying pedestal-app forward, we encourage you to fork this repository and make any changes you see fit. Once you've got something, [share it with the rest of the group](https://groups.google.com/forum/#!topic/pedestal-users/)–many folks are interested in the future of pedestal-app's ideas.

---

## Getting started

### Starting a new project

Use [leiningen](https://github.com/technomancy/leiningen) (2.2.0+) to create a new
Pedestal application. This will automatically pull templates from
<http://clojars.org>

```bash
# To create a new client-side application:
lein new pedestal-app the-next-big-thing
```

See [documentation](#documentation) for information on Pedestal concepts and
advice on getting started.

## Digging deeper

### Roadmap

Our primary focus for the near future is Pedestal documentation, sample
applications and improving general ease of use.

### Documentation

In the future, the documentation will be moved into this repository.

* [Pedestal documentation](https://github.com/pedestal/docs/tree/app-snapshot/documentation) overview of
  Pedestal concepts and advice on getting started.
* API Docs: generate literate-programming-style API docs by following the
  "What about API Documentation?" instructions in the
  [Pedestal Overview](https://github.com/pedestal/docs/blob/app-snapshot/documentation/application-overview.md).

### Supported Platforms

At present Pedestal supports OSX and Linux environments. At this time we do not
support using Pedestal on a Windows environment.

**Some good news**: We will still gladly accept pull requests extending our
Windows support

**The bad news**: We will not invest significant amounts of time into
diagnosing or correcting Windows issues.

### Find out more

* Follow [@pedestal_team on Twitter](http://twitter.com/pedestal_team)
* Subscribe to [pedestal-users](https://groups.google.com/d/forum/pedestal-users)
  and [pedestal-dev](https://groups.google.com/d/forum/pedestal-dev)

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for details on contributing to Pedestal.

### Installing Libraries

To install Pedestal library components in your local Maven repository run
`lein sub install` from a local checkout of this repository.

**WARNING: This repository contains code/changes
that *does not match* resources like the [docs](https://github.com/pedestal/docs/tree/app-snapshot/documentation),
[tutorial](https://github.com/pedestal/app-tutorial/) or otherwise.**

---

## License
Copyright 2013 Relevance, Inc.

The use and distribution terms for this software are covered by the
Eclipse Public License 1.0 (http://opensource.org/licenses/eclipse-1.0)
which can be found in the file [epl-v10.html](epl-v10.html) at the root of this distribution.

By using this software in any fashion, you are agreeing to be bound by
the terms of this license.

You must not remove this notice, or any other, from this software.
