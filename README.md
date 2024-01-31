# BrainAgeWorkingGroup

A Unified Repository for BrainAge work @ TReNDsCenter 


## Getting Started

You can clone this repo onto your local file system by running:

```bash
git clone git@github.com:trendscenter/BrainAgeWorkingGroup.git
cd BrainAgeWorkingGroup
```

In order to use ALL of the shared github repositories collected in this project, run

```bash
git submodule update --init --recursive
```

To only pull a particular module, such as `LSTM_BrainAge`, run the following (after `git submodule init`)

```bash
git submodule update --remote SharedModels/LSTM_BrainAge
```

### Pulling Updates

To pull updates for particular modules, such as `LSTM_BrainAge`, run the following:

```bash
git submodule update --remote SharedModels/LSTM_BrainAge
```

To pull updates for ALL modules, run the following:

```bash
git submodule update --recursive --remote
```

## Adding a Github Repository

To add a github repository to this one, use the following command

```bash
git submodule add github_url
```