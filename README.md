# GPDB Checkman

Monitor gpdb pipelines using Checkman

## Installation

1. Install checkman:
   - Follow instructions here: https://github.com/cppforlife/checkman
1. Install fly CLI tool:
   `curl https://prod.ci.gpdb.pivotal.io/api/v1/cli?arch=amd64&platform=darwin`
1. Login to fly:
   `fly -t gpdb-prod login`   
1. `./bin/install`
