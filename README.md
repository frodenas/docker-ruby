# Ruby Dockerfile

A Dockerfile that produces a Docker Image for [Ruby](https://www.ruby-lang.org/).

## Ruby version

The `master` branch currently hosts Ruby 2.1.

Different versions of Ruby are located at the github repo [branches](https://github.com/frodenas/docker-ruby/branches).

## Usage

### Build the image

To create the image `frodenas/ruby`, execute the following command on the `docker-ruby` folder:

```
$ docker build -t frodenas/ruby .
```

### Run the image

To run the image:

```
$ docker run -ti --rm --name ruby  frodenas/ruby
```

## Copyright

Copyright (c) 2014 Ferran Rodenas. See [LICENSE](https://github.com/frodenas/docker-ruby/blob/master/LICENSE) for details.
