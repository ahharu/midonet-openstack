# midonet-openstack
Module to deploy Openstack w/ Midonet. For Development and CI purposes

# How to Run

Execute the [all-in-one-sh](all-in-one.sh) script.

# Handy Alias to update also the submodules

`git config alias.pullall '!git pull && git submodule update --init --recursive'`

Then just do

`git pullall`

# Proposed

Having a shell script accepting arguments to select which modules do you want to install

