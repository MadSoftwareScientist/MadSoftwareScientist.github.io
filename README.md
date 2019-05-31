# Mad Software Scientist Blog

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

```bash
sudo apt-get install ruby-full gcc g++ make
```

Add following lines to ```.bashrc``` -file:

```bash
export GEM_HOME="/home/tela/.gem"
export PATH="$PATH:$GEM_HOME/bin"
```

Load updated bash configuration:

```bash
source ~/.bashrc
```

Install Jekyll and Bundler:

```bash
gem install jekyll bundler
```

### Installing

Clone repository:

```bash
git clone git@github.com:MadSoftwareScientist/MadSoftwareScientist.github.io
```

Insstall dependencies:

```bash
cd MadSoftwareScientist.github.io/
bundler install
```

Run developement server:

```bash
bundle exec jekyll serve
```

## Deployment

TBD

## Authors
* [MadSoftwareScientist](https://github.com/MadSoftwareScientist/) - Initial (and so far all) work

## Licence

TBD
