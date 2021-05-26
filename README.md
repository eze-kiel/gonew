# gonew

Generate Go project template, with a Makefile.

## Installation

```
$ git clone https://github.com/eze-kiel/gonew.git
$ cd gonew/
```

Then copy it to somewhere in the scope of your `$PATH`.

## Usage

```
$ gonew my-project
```

or simply:

```
$ gonew
```

It will ask you few questions to configure everything.

Here is the project architecture:

```
my-project/
├── .git
│   ├── branches
│   ├── config
│   ├── description
│   ├── HEAD
│   ├── hooks
│   ├── info
│   ├── objects
│   └── refs
├── go.mod
├── main.go
└── Makefile
```

## License

MIT