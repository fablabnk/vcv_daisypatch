# Daisy Patch for VCV Rack: SynthLab Additions

I forked this repo and updated it in order to allow us to build virtual VCV rack plugins with DaisySP code. The original version and instructions are [here](https://github.com/Segfault1602/vcv_daisypatch)

# Prerequisites

- make a folder somewhere convienient on your system i.e. `~/Documents/SynthLab` and cd into it
- now follow the VCV rack [plugin development tutorial](https://vcvrack.com/manual/PluginDevelopmentTutorial)
- the aim is to install VCV Rack and the Rack SDK
- it's also nice to follow the tutorial all the way through to get the basics

Once done, clone this repo in your main folder too using `git clone`
From inside your main folder, things should look like this:
```
.
├── Rack2Free
├── Rack-SDK
└── vcv_daisypatch
```

Now:
`cd vcv_daisypatch`
But before trying to 'make', don't forget to:
```
export RACK_SDK=/where/you/installed/Rack-SDK
git submodule init
git submodule update 
```