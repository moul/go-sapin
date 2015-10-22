# go-sapin
:christmas_tree: drawing a christmas tree in Go

[![GoDoc](https://godoc.org/github.com/moul/go-sapin?status.svg)](https://godoc.org/github.com/moul/go-sapin)
[![](https://img.shields.io/badge/appspot-sapin--as--a--service-blue.svg)](http://sapin-as-a-service.appspot.com/)
[![Build Status](https://travis-ci.org/moul/go-sapin.svg?branch=master)](https://travis-ci.org/moul/go-sapin)
[![Coverage Status](https://coveralls.io/repos/moul/go-sapin/badge.svg?branch=master&service=github)](https://coveralls.io/github/moul/go-sapin?branch=master)

## Demo

http://sapin-as-a-service.appspot.com/

## Usage

```console
$ sapin --presents --size=5 --star --garlands=4 --color
```
![](https://raw.githubusercontent.com/moul/go-sapin/master/assets/sapin-size5-balls4-star-garlands4-color.png)

---

```console
$ sapin --size=3 --balls=4 --star --emoji
```
![](https://raw.githubusercontent.com/moul/go-sapin/master/assets/sapin-size3-balls4-star-emoji.png)

---

```console
$ sapin --size=1
   *
  ***
 *****
*******
   |
```

---

```console
$ sapin --size=2
      *
     ***
    *****
   *******
    *****
   *******
  *********
 ***********
*************
     |||
     |||
```

---

```console
$ sapin --balls=4
                   *
                  ***
                 *****
                ****@**
                 *****
                *******
               *********
              ***********
             *************
              *****@**@**
             **********@**
            ********@******
           *@***************
          ****@**@***********
         *********************
           *@************@**
          *********@*********
         ***@**********@******
        ****************@******
       @************************
      @**************************
     *****************************
       *******@*****************
      ***********@***************
     *****************************
    *************************@*****
   *******************@*************
  **********@************************
 ***********************************@*
*****************@*********************
                 |||||
                 |||||
                 |||||
                 |||||
                 |||||
```

---

```console
$ sapin -h
Usage:
  sapin [OPTIONS]

Application Options:
  -s, --size=     Size of the sapin (5)
      --balls=    Percent of balls (4)
      --garlands= Add some garlands (4)
  -c, --color     Colorize output
      --star      Add top star
  -e, --emoji     Use emojis
      --presents  Add presents

Help Options:
  -h, --help  Show this help mess
```

## Install

```console
$ go get github.com/moul/go-sapin/cmd/sapin
```

## License

MIT
