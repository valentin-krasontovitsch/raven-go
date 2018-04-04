# raven [![Build Status](https://travis-ci.org/getsentry/raven-go.png?branch=master)](https://travis-ci.org/getsentry/raven-go)

raven is a Go client for the [Sentry](https://github.com/getsentry/sentry)
event/error logging system.

- [**API Documentation**](https://godoc.org/github.com/getsentry/raven-go)
- [**Usage and Examples**](https://docs.sentry.io/clients/go/)

## Installation

```text
go get github.com/getsentry/raven-go
```

## Modifications

To use system certificates in stead of the Mozilla certificates provided by
[go-certify](github.com/certifi/gocertifi), set the environment variable
`USE_OS_CERTIFICATES` to a non-empty string.
