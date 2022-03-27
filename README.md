# go-tsz

* Package tsz implement time-series compression http://www.vldb.org/pvldb/vol8/p1816-teller.pdf in Go*

[![Master Branch](https://img.shields.io/badge/branch-master-lightgray.svg)](https://github.com/pidb/gorilla-time-series-compression/tree/master)
[![Master Build Status](https://secure.travis-ci.org/dgryski/go-tsz.svg?branch=master)](https://travis-ci.org/dgryski/go-tsz?branch=master)
[![Master Coverage Status](https://coveralls.io/repos/dgryski/go-tsz/badge.svg?branch=master&service=github)](https://coveralls.io/github/dgryski/go-tsz?branch=master)
[![Go Report Card](https://goreportcard.com/badge/github.com/pidb/gorilla-time-series-compression)](https://goreportcard.com/report/github.com/pidb/gorilla-time-series-compression)
[![GoDoc](https://godoc.org/github.com/pidb/gorilla-time-series-compression?status.svg)](http://godoc.org/github.com/pidb/gorilla-time-series-compression)

## Description
 
Package tsz implement the  Gorilla Time Series Databasetime-series compression as described in:
http://www.vldb.org/pvldb/vol8/p1816-teller.pdf


## Getting started

This application is written in Go language, please refer to the guides in https://golang.org for getting started.

This project include a Makefile that allows you to test and build the project with simple commands.
To see all available options:
```bash
make help
```

## Running all tests

Before committing the code, please check if it passes all tests using
```bash
make qa
```
