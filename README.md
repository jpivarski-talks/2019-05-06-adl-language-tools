## How to build your own language

**Hands-on demo of tools & techniques** at the [Analysis Description Language](https://indico.cern.ch/event/769263/timetable/) workshop.

   * Fermilab, May 6, 2019 at 3:20pm.
   * [Mattermost channel](https://mattermost.web.cern.ch/adl4lhcatlpc/channels/town-square)

To participate, either install all of the software on your laptop (with [conda](https://docs.conda.io/en/latest/miniconda.html)):

```bash
git clone https://github.com/jpivarski/2019-05-06-adl-language-tools.git
cd 2019-05-06-adl-language-tools
conda env create -f environment.yml   # create an isolated environment and install everything in it
conda activate adl-language-tools     # switch to that environment
conda install jupyterlab
jupyter lab                           # runs on your machine, controlled by your web browser
```

or click below to run everything in the cloud: [![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jpivarski/2019-05-06-adl-language-tools/1.1?urlpath=lab/tree/01-overview.ipynb)

_(If installation on your laptop fails, use the cloud option.)_
