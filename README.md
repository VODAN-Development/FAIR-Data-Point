# FAIR Data Point

## Overview

This repository was made by the VODAN FDP Team and is meant for the development, deployment and troubleshooting of FDPs within the VODAN Architecture. 

### Main Objective

This deployment of the FDPs is based on the FAIR Data Point implementation by the FAIR Data Team [link](https://github.com/FAIRDataTeam/FAIRDataPoint?tab=readme-ov-file). We use it as a REST API with graphical interface for cataloging datasets and for automated discovery and querying of these.

## Installation and setup instructions

- Clone this repository to a machine with docker installed.
- Adjust ClientURL to match the domain name of the server you want to expose the FDP on.
- Set certificates through e.g. letsencrypt at the path given in docker-compose.yml.
- Run the following command from the /src/ directory
    > docker compose up -d

For frequently occuring problems and troubleshooting see the issue board.

### Prerequisites and dependencies

- Docker

## Usage guide

See the usage and REST API documentation by the FAIR Data Team [link](https://docs.fairdatapoint.org/en/latest/)

## FAQ

See wiki [link](https://github.com/VODAN-Development/FAIR-Data-Point/wiki)


## Example

See [https://fairdp.colo.ba.be](https://fairdp.colo.ba.be)
See [https://fdp.tangaza.ac.ke](https://fdp.tangaza.ac.ke)
## Contributing & issue reporting

For reuse see the [license](https://github.com/VODAN-Development/FAIR-Data-Point/blob/main/LICENSE).
For contributing to this project see the [contributor file](https://github.com/VODAN-Development/FAIR-Data-Point/blob/main/CONTRIBUTING.md).
For issue reporting use the [issue board](https://github.com/VODAN-Development/FAIR-Data-Point/issues).
